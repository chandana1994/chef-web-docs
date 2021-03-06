.. THIS PAGE DOCUMENTS chef-client version 11.0

=====================================================
template
=====================================================

.. include:: ../../includes_template/includes_template.rst

.. note:: .. include:: ../../includes_notes/includes_notes_cookbook_template_erubis.rst

.. include:: ../../includes_resources/includes_resource_template_11-4.rst

Syntax
=====================================================
.. include:: ../../includes_resources/includes_resource_template_syntax_11-4.rst

Actions
=====================================================
.. include:: ../../includes_resources/includes_resource_template_actions_11-4.rst

Properties
=====================================================
.. include:: ../../includes_resources/includes_resource_template_attributes_11-4.rst

Windows File Security
-----------------------------------------------------
.. include:: ../../includes_resources_common/includes_resources_common_windows_security.rst

**Access Control Lists (ACLs)**

.. include:: ../../includes_resources_common/includes_resources_common_windows_security_acl.rst

**Inheritance**

.. include:: ../../includes_resources_common/includes_resources_common_windows_security_inherits.rst

Providers
=====================================================
.. include:: ../../includes_resources_common/includes_resources_common_provider.rst

.. include:: ../../includes_resources_common/includes_resources_common_provider_attributes.rst

.. include:: ../../includes_resources/includes_resource_template_providers.rst

Using Templates
=====================================================
.. include:: ../../includes_template/includes_template_requirements.rst

File Specificity
-----------------------------------------------------
.. include:: ../../includes_template/includes_template_specificity.rst

.. include:: ../../includes_template/includes_template_11-16_specificity_pattern.rst

.. include:: ../../includes_template/includes_template_specificity_example.rst

Host Notation
-----------------------------------------------------
.. include:: ../../includes_template/includes_template_host_notation.rst

Partial Templates
-----------------------------------------------------
.. include:: ../../includes_template/includes_template_partials.rst

render Method
+++++++++++++++++++++++++++++++++++++++++++++++++++++
.. include:: ../../includes_template/includes_template_partials_render_method.rst

Transfer Frequency
-----------------------------------------------------
.. include:: ../../includes_template/includes_template_transfer_frequency.rst

Variables
-----------------------------------------------------
.. include:: ../../includes_template/includes_template_variables.rst

Examples
=====================================================
|generic resource statement|

**Configure a file from a template**

.. include:: ../../step_resource/step_resource_template_configure_file.rst

**Configure a file from a local template**

.. include:: ../../step_resource/step_resource_template_configure_file_from_local.rst

**Configure a file using a variable map**

.. include:: ../../step_resource/step_resource_template_configure_file_with_variable_map.rst

**Use the not_if condition**

.. include:: ../../step_resource/step_resource_template_add_file_not_if_attribute_has_value.rst

.. include:: ../../step_resource/step_resource_template_add_file_not_if_ruby.rst

.. include:: ../../step_resource/step_resource_template_add_file_not_if_ruby_with_curly_braces.rst

.. include:: ../../step_resource/step_resource_template_add_file_not_if_string.rst

**Use the only_if condition**

.. include:: ../../step_resource/step_resource_template_add_file_only_if_attribute_has_value.rst

.. include:: ../../step_resource/step_resource_template_add_file_only_if_ruby.rst

.. include:: ../../step_resource/step_resource_template_add_file_only_if_string.rst

**Use a whitespace array (%w)**

.. include:: ../../step_resource/step_resource_template_use_whitespace_array.rst

**Use a relative path**

.. include:: ../../step_resource/step_resource_template_use_relative_paths.rst

**Delay notifications**

.. include:: ../../step_resource/step_resource_template_notifies_delay.rst

**Notify immediately**

.. include:: ../../step_resource/step_resource_template_notifies_run_immediately.rst

**Notify multiple resources**

.. include:: ../../step_resource/step_resource_template_notifies_multiple_resources.rst

**Reload a service**

.. include:: ../../step_resource/step_resource_template_notifies_reload_service.rst

**Restart a service when a template is modified**

.. include:: ../../step_resource/step_resource_template_notifies_restart_service_when_template_modified.rst

**Send notifications to multiple resources**

.. include:: ../../step_resource/step_resource_template_notifies_send_notifications_to_multiple_resources.rst

**Execute a command using a template**

.. include:: ../../step_resource/step_resource_execute_command_from_template.rst

**Set an IP address using variables and a template**

.. include:: ../../step_resource/step_resource_template_set_ip_address_with_variables_and_template.rst

**Add a rule to an IP table**

.. include:: ../../step_resource/step_resource_execute_add_rule_to_iptable.rst

**Apply proxy settings consistently across a Chef organization**

.. include:: ../../step_resource/step_resource_template_consistent_proxy_settings.rst

**Get template settings from a local file**

.. include:: ../../step_resource/step_resource_template_get_settings_from_local_file.rst

**Pass values from recipe to template**

.. include:: ../../step_resource/step_resource_template_pass_values_to_template_from_recipe.rst
