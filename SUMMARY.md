# Summary

* [Introduction](README.md)
  * [Getting Started](getting_started/README.md)
    * [Installing Serene From Visual Studio Marketplace](getting_started/installing_serene_from_visual_studio_gallery.md)
    * [Installing Serene Directly From Visual Studio](getting_started/installing_serene_directly_from_visual_studio.md)
    * [Instaling Serene Asp.Net Core Version with Serin](getting_started/instaling-serene-aspnet-core-version-with-serin.md)
    * [Starting Serene](getting_started/starting_serene.md)
  * [A Tour Of Serene Features](serene_tour/README.md)
    * [Theming](serene_tour/theming.md)
    * [Localization](serene_tour/localization.md)
    * [User and Role Management](serene_tour/user_and_role_management.md)
    * [Listing Pages](serene_tour/listing_pages.md)
    * [Edit Dialogs](serene_tour/edit_dialogs.md)
* Tutorials
  * [Movie Database](tutorials/movies/movies.md)
    * [Creating Movie Table](tutorials/movies/creating_movie_table.md)
    * [Generating Code For Movie Table](tutorials/movies/generating_code_for_movie_table.md)
    * [Customizing Movie Interface](tutorials/movies/customizing_movie_interface.md)
    * [Handling Movie Navigation](tutorials/movies/handling_movie_navigation.md)
    * [Customizing Quick Search](tutorials/movies/customizing_quick_search.md)
    * [Adding a Movie Kind Field](tutorials/movies/adding_a_movie_kind_field.md)
    * [Adding Movie Genres](tutorials/movies/adding_movie_genres.md)
    * [Updating Serenity Packages](tutorials/movies/updating_serenity_packages.md)
    * [Allowing Multiple Genre Selection](tutorials/movies/allowing_multiple_genre_selection.md)
    * [Filtering with Multiple Genre List](tutorials/movies/filtering_with_multiple_genre_list.md)
    * [The Cast and Characters They Played](tutorials/movies/the_cast_and_characters_they_played.md)
    * [Listing Movies in Person Dialog](tutorials/movies/listing_movies_in_person_dialog.md)
    * [Adding Primary and Gallery Images](tutorials/movies/adding_primary_and_gallery_images.md)
  * [Multi Tenancy](tutorials/multi_tenancy/multi_tenancy.md)
    * [Adding Tenants Table and TenantId Field](tutorials/multi_tenancy/adding_tenants_table_and_tenantid_field.md)
    * [Generating Code for Tenants Table](tutorials/multi_tenancy/generating_code_for_tenants_table.md)
    * [Tenant Selection in User Dialog](tutorials/multi_tenancy/tenant_selection_in_user_dialog.md)
    * [Filtering Users By TenantId](tutorials/multi_tenancy/filtering_users_by_tenantid.md)
    * [Removing Tenant Dropdown From User Form](tutorials/multi_tenancy/removing_tenant_dropdown_from_user_form.md)
    * [Securing Tenant Selection At Server Side](tutorials/multi_tenancy/securing_tenant_selection_at_server_side.md)
    * [Setting TenantId For New Users](tutorials/multi_tenancy/setting_tenantid_for_new_users.md)
    * [Preventing Edits To Users From Other Tenants](tutorials/multi_tenancy/preventing_edits_to_users_from_other_tenants.md)
    * [Hiding the Tenant Administration Permission](tutorials/multi_tenancy/hiding_the_tenant_administration_permission.md)
    * [Making Roles Multi-Tenant](tutorials/multi_tenancy/making_roles_multi-tenant.md)
    * [Using Serenity Service Behaviors](tutorials/multi_tenancy/using_serenity_service_behaviors.md)
    * [Extending Multi-Tenant Behavior To Northwind](tutorials/multi_tenancy/extending_multi-tenant_behavior_to_northwind.md)
    * [Handling Lookup Scripts](tutorials/multi_tenancy/handling_lookup_scripts.md)
* Knowledge Base
  * How To Guides
    * [Update Serenity NuGet Packages](howto/how_to_update_serenity_nuget_packages.md)
    * [Remove Northwind & Other Samples From Serene](howto/removing_northwind.md)
    * [Authenticate With Active Directory or LDAP](howto/how_to_authenticate_with_active_directory_or_ldap.md)
    * [Enable Script Bundling](howto/how_to_enable_script_bundling.md)
    * [Debugging with Serenity Sources](howto/how_to_debugging_with_serenity_sources.md)
    * [Add a Row Selection Column](howto/how_to_add_a_row_selection_column.md)
    * [Setup Cascaded Editors](howto/how_to_setup_cascaded_editors.md)
    * [Use Recaptcha](howto/how_to_use_recaptcha.md)
    * [Register Permissions in Serene](howto/how_to_register_permissions_in_serene.md)
    * [Use a Third Party Plugin With Serenity](howto/how_to_use_a_third_party_plugin_with_serenity.md)
    * [Use a SlickGrid Formatter](howto/how_to_use_a_slickgrid_formatter.md)
    * [Upgrade to Serenity 2.0 and Enable TypeScript](howto/how_to_upgrade_to_serenity_2_typescript.md)
  * [Frequently Asked Questions](faq/frequently_asked_questions.md)
  * [Troubleshooting](faq/troubleshooting.md)
* Framework Features
  * [Service Locator & Initialization](service_locator/README.md)
    * [Dependency Static Class](service_locator/dependency_static_class.md)
    * [IDependencyResolver Interface](service_locator/idependencyresolver_interface.md)
    * [IDependencyRegistrar Interface](service_locator/idependencyregistrar_interface.md)
    * [MunqContainer Class](service_locator/munqcontainer_class.md)
    * [CommonInitialization Static Class](service_locator/commoninitialization_static_class.md)
  * [Authentication & Authorization](authentication/README.md)
    * [IAuthenticationService Interface](authentication/iauthenticationservice_interface.md)
    * [IAuthorizationService Interface](authentication/iauthorizationservice_interface.md)
    * [IPermissionService Interface](authentication/ipermissionservice_interface.md)
    * [IUserDefinition Interface](authentication/iuserdefinition_interface.md)
    * [IUserRetrieveService Interface](authentication/iuserretrieveservice_interface.md)
    * [Authorization Static Class](authentication/authorization_static_class.md)
  * [Configuration System](configuration_system/README.md)
    * [Defining Configuration Settings](configuration_system/defining_configuration_settings.md)
    * [IConfigurationRepository Interface](configuration_system/iconfigurationrepository_interface.md)
    * [AppSettingsJsonConfigRepository](configuration_system/appsettingsjsonconfigrepository.md)
    * [Config Static Class](configuration_system/config_static_class.md)
  * [Localization](localization/README.md)
    * [LocalText Class](localization/localtext_class.md)
    * [Language Identifiers](localization/language_identifiers.md)
    * [Language Fallbacks](localization/language_fallbacks.md)
    * [ILocalTextRegistry Interface](localization/ilocaltextregistry_interface.md)
    * [LocalTextRegistry Class](localization/localtextregistry_class.md)
      * [Pending Approval Mode](localization/pending_approval_mode.md)
    * [Registering Translations](localization/registering_translations.md)
      * [Manually Registering Translations](localization/manually_registering_translations.md)
      * [Nested Local Texts](localization/nested_local_texts.md)
      * [Enumeration Texts](localization/enumeration_texts.md)
      * [JSON Local Texts](localization/json_local_texts.md)
  * [Caching](caching/README.md)
    * [Local Caching](caching/local_caching.md)
      * [ILocalCache Interface](caching/ilocalcache_interface.md)
      * [LocalCache Static Class](caching/localcache_static_class.md)
      * [User Profile Caching Sample](caching/user_profile_caching_sample.md)
    * [Distributed Caching](caching/distributed_caching.md)
      * [WEB Farms and Caching](caching/web_farms_and_caching.md)
      * [IDistributedCache Interface](caching/idistributedcache_interface.md)
      * [Distributed Cache Static Class](caching/distributed_cache_static_class.md)
      * [DistributedCacheEmulator Class](caching/distributedcacheemulator_class.md)
      * [CouchbaseDistributedCache Class](caching/couchbasedistributedcache_class.md)
      * [RedisDistributedCache Class](caching/redisdistributedcache_class.md)
    * [Two Level Caching](caching/two_level_caching.md)
      * [Using Local Cache and Distributed Cache In Sync](caching/using_local_cache_and_distributed_cache_in_sync.md)
      * [TwoLevelCache Class](caching/twolevelcache_class.md)
  * Data Access
    * [Entities \(Row\)](entities/entities_row.md)
      * [Mapping Attributes](entities/mapping_attributes.md)
      * [FieldFlags Enumeration](entities/fieldflags_enumeration.md)
    * [Fluent SQL](fluent_sql/fluent_sql.md)
      * [SqlQuery Object](fluent_sql/sqlquery_object.md)
      * [Criteria Objects](fluent_sql/criteria_objects.md)
    * [Connections and Transactions](connections/connections_and_transactions.md)
    * SQL Database Types
    * [Working with Other Databases](work-with-other-database-types.md)
      * [Setting Connection Dialect](setting-connection-dialect.md)
      * [Dialect Based Expressions](dialect-based-expressions.md)
      * [PostgreSQL](postgresql.md)
      * [MySQL](mysql.md)
      * [Sqlite](sqlite.md)
      * [Oracle](oracle.md)
  * [Services](services/README.md)
    * [Service Endpoints](services/service_endpoints.md)
    * [List Request Handler](services/list_request_handler.md)
  * UI
    * Forms & Grids
      * [Attributes](attributes/attributes.md)
      * [Grids](grids/readme.md)
        * [Formatter Types](grids/formatter_types.md)
        * [Persisting Settings](grids/persisting_settings.md)
    * Script Classes
      * [Widgets](widgets/README.md)
      * [ScriptContext Class](widgets/scriptcontext_class.md)
      * [Widget Class](widgets/widget_class.md)
      * [Widget With Options](widgets/widget_with_options.md)
      * [TemplatedWidget Class](widgets/templated_widget_class.md)
      * [TemplatedDialog Class](widgets/templated_dialog_class.md)
  * [Code Generator \(Sergen\)](sergen/code_generator_sergen.md)
* [Used Tools & Libraries](getting_started/used_tools_and_libraries.md)

