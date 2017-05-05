.. This work is lit_snapshots_list_details_with_paramsensed under a Creative Commons Attribution 4.0 International License.
.. http://creativecommons.org/licenses/by/4.0
.. (c) Ericsson AB

=======================================================
Compliance and Verification program accepted test cases
=======================================================

.. toctree::
    :maxdepth: 2


Mandatory CVP Test Areas
========================

----------------------------------
Test Area VIM Operations - Compute
----------------------------------

Image operations within the Compute API
---------------------------------------
tempest.api.compute.images.test_images_oneserver.ImagesOneServerTestJSON.test_create_delete_image
tempest.api.compute.images.test_images_oneserver.ImagesOneServerTestJSON.test_create_image_specify_multibyte_character_image_name


Basic support Compute API for server actions such as reboot, rebuild, resize
----------------------------------------------------------------------------
tempest.api.compute.servers.test_instance_actions.InstanceActionsTestJSON.test_get_instance_action
tempest.api.compute.servers.test_instance_actions.InstanceActionsTestJSON.test_list_instance_actions


Generate, import, and delete SSH keys within Compute services
-------------------------------------------------------------
tempest.api.compute.servers.test_servers.ServersTestJSON.test_create_specify_keypair


List supported versions of the Compute API
------------------------------------------
tempest.api.compute.test_versions.TestVersions.test_list_api_versions


Quotas management in Compute API
--------------------------------
tempest.api.compute.test_quotas.QuotasTestJSON.test_get_default_quotas
tempest.api.compute.test_quotas.QuotasTestJSON.test_get_quotas


Basic server operations in the Compute API
------------------------------------------
tempest.api.compute.servers.test_servers.ServersTestJSON.test_create_server_with_admin_password
tempest.api.compute.servers.test_servers.ServersTestJSON.test_create_with_existing_server_name
tempest.api.compute.servers.test_servers_negative.ServersNegativeTestJSON.test_create_numeric_server_name
tempest.api.compute.servers.test_servers_negative.ServersNegativeTestJSON.test_create_server_metadata_exceeds_length_limit
tempest.api.compute.servers.test_servers_negative.ServersNegativeTestJSON.test_create_server_name_length_exceeds_256
tempest.api.compute.servers.test_servers_negative.ServersNegativeTestJSON.test_create_with_invalid_flavor
tempest.api.compute.servers.test_servers_negative.ServersNegativeTestJSON.test_create_with_invalid_image
tempest.api.compute.servers.test_servers_negative.ServersNegativeTestJSON.test_create_with_invalid_network_uuid
tempest.api.compute.servers.test_servers_negative.ServersNegativeTestJSON.test_delete_server_pass_id_exceeding_length_limit
tempest.api.compute.servers.test_servers_negative.ServersNegativeTestJSON.test_delete_server_pass_negative_id
tempest.api.compute.servers.test_servers_negative.ServersNegativeTestJSON.test_get_non_existent_server
tempest.api.compute.servers.test_create_server.ServersTestJSON.test_host_name_is_same_as_server_name
tempest.api.compute.servers.test_create_server.ServersTestManualDisk.test_host_name_is_same_as_server_name
tempest.api.compute.servers.test_servers_negative.ServersNegativeTestJSON.test_invalid_ip_v6_address
tempest.api.compute.servers.test_create_server.ServersTestJSON.test_list_servers
tempest.api.compute.servers.test_create_server.ServersTestJSON.test_list_servers_with_detail
tempest.api.compute.servers.test_create_server.ServersTestManualDisk.test_list_servers
tempest.api.compute.servers.test_create_server.ServersTestManualDisk.test_list_servers_with_detail
tempest.api.compute.servers.test_list_server_filters.ListServerFiltersTestJSON.test_list_servers_detailed_filter_by_flavor
tempest.api.compute.servers.test_list_server_filters.ListServerFiltersTestJSON.test_list_servers_detailed_filter_by_image
tempest.api.compute.servers.test_list_server_filters.ListServerFiltersTestJSON.test_list_servers_detailed_filter_by_server_name
tempest.api.compute.servers.test_list_server_filters.ListServerFiltersTestJSON.test_list_servers_detailed_filter_by_server_status
tempest.api.compute.servers.test_list_server_filters.ListServerFiltersTestJSON.test_list_servers_detailed_limit_results
tempest.api.compute.servers.test_list_server_filters.ListServerFiltersTestJSON.test_list_servers_filter_by_flavor
tempest.api.compute.servers.test_list_server_filters.ListServerFiltersTestJSON.test_list_servers_filter_by_image
tempest.api.compute.servers.test_list_server_filters.ListServerFiltersTestJSON.test_list_servers_filter_by_limit
tempest.api.compute.servers.test_list_server_filters.ListServerFiltersTestJSON.test_list_servers_filter_by_server_name
tempest.api.compute.servers.test_list_server_filters.ListServerFiltersTestJSON.test_list_servers_filter_by_server_status
tempest.api.compute.servers.test_list_server_filters.ListServerFiltersTestJSON.test_list_servers_filtered_by_name_wildcard
tempest.api.compute.servers.test_list_servers_negative.ListServersNegativeTestJSON.test_list_servers_by_changes_since_future_date
tempest.api.compute.servers.test_list_servers_negative.ListServersNegativeTestJSON.test_list_servers_by_changes_since_invalid_date
tempest.api.compute.servers.test_list_servers_negative.ListServersNegativeTestJSON.test_list_servers_by_limits
tempest.api.compute.servers.test_list_servers_negative.ListServersNegativeTestJSON.test_list_servers_by_limits_greater_than_actual_count
tempest.api.compute.servers.test_list_servers_negative.ListServersNegativeTestJSON.test_list_servers_by_limits_pass_negative_value
tempest.api.compute.servers.test_list_servers_negative.ListServersNegativeTestJSON.test_list_servers_by_limits_pass_string
tempest.api.compute.servers.test_list_servers_negative.ListServersNegativeTestJSON.test_list_servers_by_non_existing_flavor
tempest.api.compute.servers.test_list_servers_negative.ListServersNegativeTestJSON.test_list_servers_by_non_existing_image
tempest.api.compute.servers.test_list_servers_negative.ListServersNegativeTestJSON.test_list_servers_by_non_existing_server_name
tempest.api.compute.servers.test_list_servers_negative.ListServersNegativeTestJSON.test_list_servers_detail_server_is_deleted
tempest.api.compute.servers.test_list_servers_negative.ListServersNegativeTestJSON.test_list_servers_status_non_existing
tempest.api.compute.servers.test_list_servers_negative.ListServersNegativeTestJSON.test_list_servers_with_a_deleted_server
tempest.api.compute.servers.test_server_actions.ServerActionsTestJSON.test_lock_unlock_server
tempest.api.compute.servers.test_server_metadata.ServerMetadataTestJSON.test_delete_server_metadata_item
tempest.api.compute.servers.test_server_metadata.ServerMetadataTestJSON.test_get_server_metadata_item
tempest.api.compute.servers.test_server_metadata.ServerMetadataTestJSON.test_list_server_metadata
tempest.api.compute.servers.test_server_metadata.ServerMetadataTestJSON.test_set_server_metadata
tempest.api.compute.servers.test_server_metadata.ServerMetadataTestJSON.test_set_server_metadata_item
tempest.api.compute.servers.test_server_metadata.ServerMetadataTestJSON.test_update_server_metadata
tempest.api.compute.servers.test_servers_negative.ServersNegativeTestJSON.test_server_name_blank
tempest.api.compute.servers.test_server_actions.ServerActionsTestJSON.test_reboot_server_hard
tempest.api.compute.servers.test_servers_negative.ServersNegativeTestJSON.test_reboot_non_existent_server
tempest.api.compute.servers.test_server_actions.ServerActionsTestJSON.test_rebuild_server
tempest.api.compute.servers.test_servers_negative.ServersNegativeTestJSON.test_rebuild_deleted_server
tempest.api.compute.servers.test_servers_negative.ServersNegativeTestJSON.test_rebuild_non_existent_server
tempest.api.compute.servers.test_server_actions.ServerActionsTestJSON.test_stop_start_server
tempest.api.compute.servers.test_servers_negative.ServersNegativeTestJSON.test_stop_non_existent_server
tempest.api.compute.servers.test_servers.ServersTestJSON.test_update_access_server_address
tempest.api.compute.servers.test_servers.ServersTestJSON.test_update_server_name
tempest.api.compute.servers.test_servers_negative.ServersNegativeTestJSON.test_update_name_of_non_existent_server
tempest.api.compute.servers.test_servers_negative.ServersNegativeTestJSON.test_update_server_name_length_exceeds_256
tempest.api.compute.servers.test_servers_negative.ServersNegativeTestJSON.test_update_server_set_empty_name
tempest.api.compute.servers.test_create_server.ServersTestJSON.test_verify_created_server_vcpus
tempest.api.compute.servers.test_create_server.ServersTestJSON.test_verify_server_details
tempest.api.compute.servers.test_create_server.ServersTestManualDisk.test_verify_created_server_vcpus
tempest.api.compute.servers.test_create_server.ServersTestManualDisk.test_verify_server_details


Retrieve volume information through the Compute API
---------------------------------------------------
tempest.api.compute.volumes.test_attach_volume.AttachVolumeTestJSON.test_attach_detach_volume
tempest.api.compute.volumes.test_attach_volume.AttachVolumeTestJSON.test_list_get_volume_attachments



-----------------------------------
Test Area VIM Operations - Identity
-----------------------------------

API discovery operations within the Identity v3 API
---------------------------------------------------
tempest.api.identity.v3.test_api_discovery.TestApiDiscovery.test_api_media_types
tempest.api.identity.v3.test_api_discovery.TestApiDiscovery.test_api_version_resources
tempest.api.identity.v3.test_api_discovery.TestApiDiscovery.test_api_version_statuses


Auth operations within the Identity API
---------------------------------------
tempest.api.identity.v3.test_tokens.TokensV3Test.test_create_token



--------------------------------
Test Area VIM Operations - Image
--------------------------------

Image deletion tests using the Glance v2 API
--------------------------------------------
tempest.api.image.v2.test_images.BasicOperationsImagesTest.test_delete_image
tempest.api.image.v2.test_images_negative.ImagesNegativeTest.test_delete_image_null_id
tempest.api.image.v2.test_images_negative.ImagesNegativeTest.test_delete_non_existing_image
tempest.api.image.v2.test_images_tags_negative.ImagesTagsNegativeTest.test_delete_non_existing_tag


Image get tests using the Glance v2 API
---------------------------------------
tempest.api.image.v2.test_images.ListImagesTest.test_get_image_schema
tempest.api.image.v2.test_images.ListImagesTest.test_get_images_schema
tempest.api.image.v2.test_images_negative.ImagesNegativeTest.test_get_delete_deleted_image
tempest.api.image.v2.test_images_negative.ImagesNegativeTest.test_get_image_null_id
tempest.api.image.v2.test_images_negative.ImagesNegativeTest.test_get_non_existent_image


CRUD image operations in Images API v2
--------------------------------------
tempest.api.image.v2.test_images.ListImagesTest.test_list_no_params


Image list tests using the Glance v2 API
----------------------------------------
tempest.api.image.v2.test_images.ListImagesTest.test_list_images_param_container_format
tempest.api.image.v2.test_images.ListImagesTest.test_list_images_param_disk_format
tempest.api.image.v2.test_images.ListImagesTest.test_list_images_param_limit
tempest.api.image.v2.test_images.ListImagesTest.test_list_images_param_min_max_size
tempest.api.image.v2.test_images.ListImagesTest.test_list_images_param_size
tempest.api.image.v2.test_images.ListImagesTest.test_list_images_param_status
tempest.api.image.v2.test_images.ListImagesTest.test_list_images_param_visibility


Image update tests using the Glance v2 API
------------------------------------------
tempest.api.image.v2.test_images.BasicOperationsImagesTest.test_update_image
tempest.api.image.v2.test_images_tags.ImagesTagsTest.test_update_delete_tags_for_image
tempest.api.image.v2.test_images_tags_negative.ImagesTagsNegativeTest.test_update_tags_for_non_existing_image


----------------------------------
Test Area VIM Operations - Network
----------------------------------

Basic CRUD operations on L2 networks and L2 network ports
---------------------------------------------------------

tempest.api.network.test_networks.NetworksTest.test_create_delete_subnet_all_attributes
tempest.api.network.test_networks.NetworksTest.test_create_delete_subnet_with_allocation_pools
tempest.api.network.test_networks.NetworksTest.test_create_delete_subnet_with_dhcp_enabled
tempest.api.network.test_networks.NetworksTest.test_create_delete_subnet_with_gw
tempest.api.network.test_networks.NetworksTest.test_create_delete_subnet_with_gw_and_allocation_pools
tempest.api.network.test_networks.NetworksTest.test_create_delete_subnet_with_host_routes_and_dns_nameservers
tempest.api.network.test_networks.NetworksTest.test_create_delete_subnet_without_gateway
tempest.api.network.test_networks.NetworksTest.test_create_update_delete_network_subnet
tempest.api.network.test_networks.NetworksTest.test_delete_network_with_subnet
tempest.api.network.test_networks.NetworksTest.test_list_networks
tempest.api.network.test_networks.NetworksTest.test_list_networks_fields
tempest.api.network.test_networks.NetworksTest.test_list_subnets
tempest.api.network.test_networks.NetworksTest.test_list_subnets_fields
tempest.api.network.test_networks.NetworksTest.test_show_network
tempest.api.network.test_networks.NetworksTest.test_show_network_fields
tempest.api.network.test_networks.NetworksTest.test_show_subnet
tempest.api.network.test_networks.NetworksTest.test_show_subnet_fields
tempest.api.network.test_networks.NetworksTest.test_update_subnet_gw_dns_host_routes_dhcp
tempest.api.network.test_ports.PortsTestJSON.test_create_bulk_port
tempest.api.network.test_ports.PortsTestJSON.test_create_port_in_allowed_allocation_pools
tempest.api.network.test_ports.PortsTestJSON.test_create_update_delete_port
tempest.api.network.test_ports.PortsTestJSON.test_list_ports
tempest.api.network.test_ports.PortsTestJSON.test_list_ports_fields
tempest.api.network.test_ports.PortsTestJSON.test_show_port
tempest.api.network.test_ports.PortsTestJSON.test_show_port_fields
tempest.api.network.test_ports.PortsTestJSON.test_update_port_with_security_group_and_extra_attributes
tempest.api.network.test_ports.PortsTestJSON.test_update_port_with_two_security_groups_and_extra_attributes


Basic CRUD operations on security groups
----------------------------------------
tempest.api.network.test_security_groups.SecGroupTest.test_create_list_update_show_delete_security_group
tempest.api.network.test_security_groups.SecGroupTest.test_create_security_group_rule_with_additional_args
tempest.api.network.test_security_groups.SecGroupTest.test_create_security_group_rule_with_icmp_type_code
tempest.api.network.test_security_groups.SecGroupTest.test_create_security_group_rule_with_protocol_integer_value
tempest.api.network.test_security_groups.SecGroupTest.test_create_security_group_rule_with_remote_group_id
tempest.api.network.test_security_groups.SecGroupTest.test_create_security_group_rule_with_remote_ip_prefix
tempest.api.network.test_security_groups.SecGroupTest.test_create_show_delete_security_group_rule
tempest.api.network.test_security_groups.SecGroupTest.test_list_security_groups
tempest.api.network.test_security_groups_negative.NegativeSecGroupTest.test_create_additional_default_security_group_fails
tempest.api.network.test_security_groups_negative.NegativeSecGroupTest.test_create_duplicate_security_group_rule_fails
tempest.api.network.test_security_groups_negative.NegativeSecGroupTest.test_create_security_group_rule_with_bad_ethertype
tempest.api.network.test_security_groups_negative.NegativeSecGroupTest.test_create_security_group_rule_with_bad_protocol
tempest.api.network.test_security_groups_negative.NegativeSecGroupTest.test_create_security_group_rule_with_bad_remote_ip_prefix
tempest.api.network.test_security_groups_negative.NegativeSecGroupTest.test_create_security_group_rule_with_invalid_ports
tempest.api.network.test_security_groups_negative.NegativeSecGroupTest.test_create_security_group_rule_with_non_existent_remote_groupid
tempest.api.network.test_security_groups_negative.NegativeSecGroupTest.test_create_security_group_rule_with_non_existent_security_group
tempest.api.network.test_security_groups_negative.NegativeSecGroupTest.test_delete_non_existent_security_group
tempest.api.network.test_security_groups_negative.NegativeSecGroupTest.test_show_non_existent_security_group
tempest.api.network.test_security_groups_negative.NegativeSecGroupTest.test_show_non_existent_security_group_rule


---------------------------------
Test Area VIM Operations - Volume
---------------------------------

Volume attach and detach operations with the Cinder v2 API
----------------------------------------------------------
tempest.api.volume.test_volumes_actions.VolumesV2ActionsTest.test_attach_detach_volume_to_instance
tempest.api.volume.test_volumes_actions.VolumesV2ActionsTest.test_get_volume_attachment
tempest.api.volume.test_volumes_negative.VolumesV2NegativeTest.test_attach_volumes_with_nonexistent_volume_id
tempest.api.volume.test_volumes_negative.VolumesV2NegativeTest.test_detach_volumes_with_invalid_volume_id


Volume service availability zone operations with the Cinder v2 API
------------------------------------------------------------------
tempest.api.volume.test_availability_zone.AvailabilityZoneV2TestJSON.test_get_availability_zone_list


Volume cloning operations with the Cinder v2 API
------------------------------------------------
tempest.api.volume.test_volumes_get.VolumesV2GetTest.test_volume_create_get_update_delete_as_clone


Image copy-to-volume operations with the Cinder v2 API
------------------------------------------------------
tempest.api.volume.test_volumes_actions.VolumesV2ActionsTest.test_volume_bootable
tempest.api.volume.test_volumes_get.VolumesV2GetTest.test_volume_create_get_update_delete_from_image


Volume creation and deletion operations with the Cinder v2 API
--------------------------------------------------------------
tempest.api.volume.test_volumes_get.VolumesV2GetTest.test_volume_create_get_update_delete
tempest.api.volume.test_volumes_negative.VolumesV2NegativeTest.test_create_volume_with_invalid_size
tempest.api.volume.test_volumes_negative.VolumesV2NegativeTest.test_create_volume_with_nonexistent_source_volid
tempest.api.volume.test_volumes_negative.VolumesV2NegativeTest.test_create_volume_with_nonexistent_volume_type
tempest.api.volume.test_volumes_negative.VolumesV2NegativeTest.test_create_volume_with_out_passing_size
tempest.api.volume.test_volumes_negative.VolumesV2NegativeTest.test_create_volume_with_size_negative
tempest.api.volume.test_volumes_negative.VolumesV2NegativeTest.test_create_volume_with_size_zero


Volume service extension listing operations with the Cinder v2 API
------------------------------------------------------------------
tempest.api.volume.test_extensions.ExtensionsV2TestJSON.test_list_extensions


Volume GET operations with the Cinder v2 API
--------------------------------------------
tempest.api.volume.test_volumes_negative.VolumesV2NegativeTest.test_get_invalid_volume_id
tempest.api.volume.test_volumes_negative.VolumesV2NegativeTest.test_get_volume_without_passing_volume_id
tempest.api.volume.test_volumes_negative.VolumesV2NegativeTest.test_volume_get_nonexistent_volume_id

Volume listing operations with the Cinder v2 API
------------------------------------------------
tempest.api.volume.test_volumes_list.VolumesV2ListTestJSON.test_volume_list
tempest.api.volume.test_volumes_list.VolumesV2ListTestJSON.test_volume_list_by_name
tempest.api.volume.test_volumes_list.VolumesV2ListTestJSON.test_volume_list_details_by_name
tempest.api.volume.test_volumes_list.VolumesV2ListTestJSON.test_volume_list_param_display_name_and_status
tempest.api.volume.test_volumes_list.VolumesV2ListTestJSON.test_volume_list_with_detail_param_display_name_and_status
tempest.api.volume.test_volumes_list.VolumesV2ListTestJSON.test_volume_list_with_detail_param_metadata
tempest.api.volume.test_volumes_list.VolumesV2ListTestJSON.test_volume_list_with_details
tempest.api.volume.test_volumes_list.VolumesV2ListTestJSON.test_volume_list_with_param_metadata
tempest.api.volume.test_volumes_list.VolumesV2ListTestJSON.test_volumes_list_by_availability_zone
tempest.api.volume.test_volumes_list.VolumesV2ListTestJSON.test_volumes_list_by_status
tempest.api.volume.test_volumes_list.VolumesV2ListTestJSON.test_volumes_list_details_by_availability_zone
tempest.api.volume.test_volumes_list.VolumesV2ListTestJSON.test_volumes_list_details_by_status
tempest.api.volume.test_volumes_negative.VolumesV2NegativeTest.test_list_volumes_detail_with_invalid_status
tempest.api.volume.test_volumes_negative.VolumesV2NegativeTest.test_list_volumes_detail_with_nonexistent_name
tempest.api.volume.test_volumes_negative.VolumesV2NegativeTest.test_list_volumes_with_invalid_status
tempest.api.volume.test_volumes_negative.VolumesV2NegativeTest.test_list_volumes_with_nonexistent_name
tempest.api.volume.v2.test_volumes_list.VolumesV2ListTestJSON.test_volume_list_details_pagination
tempest.api.volume.v2.test_volumes_list.VolumesV2ListTestJSON.test_volume_list_details_with_multiple_params
tempest.api.volume.v2.test_volumes_list.VolumesV2ListTestJSON.test_volume_list_pagination


Volume metadata operations with the Cinder v2 API
-------------------------------------------------

tempest.api.volume.test_volume_metadata.VolumesV2MetadataTest.test_create_get_delete_volume_metadata
tempest.api.volume.test_volume_metadata.VolumesV2MetadataTest.test_update_volume_metadata_item


Verification of read-only status on volumes with the Cinder v2 API
------------------------------------------------------------------
tempest.api.volume.test_volumes_actions.VolumesV2ActionsTest.test_volume_readonly_update


Volume reservation operations with the Cinder v2 API
----------------------------------------------------
tempest.api.volume.test_volumes_actions.VolumesV2ActionsTest.test_reserve_unreserve_volume
tempest.api.volume.test_volumes_negative.VolumesV2NegativeTest.test_reserve_volume_with_negative_volume_status
tempest.api.volume.test_volumes_negative.VolumesV2NegativeTest.test_reserve_volume_with_nonexistent_volume_id
tempest.api.volume.test_volumes_negative.VolumesV2NegativeTest.test_unreserve_volume_with_nonexistent_volume_id


Volume snapshot creation/deletion operations with the Cinder v2 API
-------------------------------------------------------------------
tempest.api.volume.test_snapshot_metadata.SnapshotV2MetadataTestJSON.test_create_get_delete_snapshot_metadata
tempest.api.volume.test_snapshot_metadata.SnapshotV2MetadataTestJSON.test_update_snapshot_metadata_item
tempest.api.volume.test_volumes_negative.VolumesV2NegativeTest.test_create_volume_with_nonexistent_snapshot_id
tempest.api.volume.test_volumes_negative.VolumesV2NegativeTest.test_delete_invalid_volume_id
tempest.api.volume.test_volumes_negative.VolumesV2NegativeTest.test_delete_volume_without_passing_volume_id
tempest.api.volume.test_volumes_negative.VolumesV2NegativeTest.test_volume_delete_nonexistent_volume_id
tempest.api.volume.test_volumes_snapshots.VolumesV2SnapshotTestJSON.test_snapshot_create_get_list_update_delete
tempest.api.volume.test_volumes_snapshots.VolumesV2SnapshotTestJSON.test_volume_from_snapshot
tempest.api.volume.test_volumes_snapshots.VolumesV2SnapshotTestJSON.test_snapshots_list_details_with_params
tempest.api.volume.test_volumes_snapshots.VolumesV2SnapshotTestJSON.test_snapshots_list_with_params
tempest.api.volume.test_volumes_snapshots_negative.VolumesV2SnapshotNegativeTestJSON.test_create_snapshot_with_nonexistent_volume_id
tempest.api.volume.test_volumes_snapshots_negative.VolumesV2SnapshotNegativeTestJSON.test_create_snapshot_without_passing_volume_id


Volume update operations with the Cinder v2 API
-----------------------------------------------
tempest.api.volume.test_volumes_negative.VolumesV2NegativeTest.test_update_volume_with_empty_volume_id
tempest.api.volume.test_volumes_negative.VolumesV2NegativeTest.test_update_volume_with_invalid_volume_id
tempest.api.volume.test_volumes_negative.VolumesV2NegativeTest.test_update_volume_with_nonexistent_volume_id



Optional CVP Test Areas
========================
