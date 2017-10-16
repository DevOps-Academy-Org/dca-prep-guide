# Docker Certified Associate Preparation Guide
This guide is a collection of all the resources needed to prepare for the [Docker Certified Associate certification](https://success.docker.com/Certification).  
It is the first official certification from the professional certificaton program for the Docker Enterprise Edition and was [announced in September 2017](https://blog.docker.com/tag/docker-certified-associate/).
To pass the examination you need to answer 55 questions in 80 minutes.

The [Docker Certified Associate Study Guide](https://prismic-io.s3.amazonaws.com/docker%2F8fb020bf-fe21-409c-ba02-7e0fd18276d5_dca+study+guide+v1.0.pdf) is the official source for all
the knowledge domains that are covered by the certification questions.

As the Docker Certified Associate Study Guide only gives a broad overview of the relevant areas, this guides tries to compile a comprehensive list of resources to help
prepare for the certification. 

For all certification topics it includes a list of relevant official Docker documentation, third party resources like blog posts, preparation hints and where
available interactive [Play with Docker](http://training.play-with-docker.com/alacart/) examples or code samples.

Please help us to make this the best source for preparing for the Docker Certified Associate certification by sharing the resources that helped you pass the examination.
Pull requests are very welcome!


## Current status
|Domain|Official Documentation|Third Party Resources|Play with Docker Examples|Ascii Cinema Examples|Preparation Hints|
|------|:--------------------:|:-------------------:|:-----------------------:|:-------------------:|:---------------:|
|1     |Work in Progress      |                     |                         |                     |                 |
|2     |Work in Progress      |                     |                         |                     |                 |
|3     |                      |                     |                         |                     |                 |
|4     |                      |                     |                         |                     |                 |
|5     |                      |                     |                         |                     |                 |
|6     |                      |                     |                         |                     |                 |

## Content
### Domain 1: Orchestration (25% of exam)
Content may include the following:
- [Complete the setup of a swarm mode cluster with managers and worker nodes](domain1/Complete_the_setup_of_a_swarm_mode_cluster_with_managers_and_worker_nodes.md)
- [State the differences between running a container vs running a service](domain1/State_the_differences_between_running_a_container_vs_running_a_service.md)
- [Demonstrate steps to lock a swarm cluster](domain1/Demonstrate_steps_to_lock_a_swarm_cluster.md)
- [Extend the instructions to run individual containers into running services under swarm](domain1/Extend_the_instructions_to_run_individual_containers_into_running_services_under_swarm.md)
- [Interpret the output of docker inspect commands](domain1/Interpret_the_output_of_docker_inspect_commands.md)
- [Convert an application deployment into a stack file using a YAML compose file with docker stack deploy](domain1/Convert_an_application_deployment_into_a_stack_file_using_a_YAML_compose_file_with_docker_stack_deploy.md)
- [Manipulate a running stack of services](domain1/Manipulate_a_running_stack_of_services.md)
- [Increase number of replicas](domain1/Increase_number_of_replicas.md)
- [Add networks publish ports](domain1/Add_networks_publish_ports.md)
- [Mount volumes](domain1/Mount_volumes.md)
- [Illustrate running a replicated vs global service](domain1/Illustrate_running_a_replicated_vs_global_service.md)
- [Identify the steps needed to troubleshoot a service not deploying](domain1/Identify_the_steps_needed_to_troubleshoot_a_service_not_deploying.md)
- [Apply node labels to demonstrate placement of tasks](domain1/Apply_node_labels_to_demonstrate_placement_of_tasks.md)
- [Sketch how a Dockerized application communicates with legacy systems](domain1/Sketch_how_a_Dockerized_application_communicates_with_legacy_systems.md)
- [Paraphrase the importance of quorum in a swarm cluster](domain1/Paraphrase_the_importance_of_quorum_in_a_swarm_cluster.md)
- [Demonstrate the usage of templates with docker service create](domain1/Demonstrate_the_usage_of_templates_with_docker_service_create.md)

### Domain 2: Image Creation, Management, and Registry (20% of exam)
Content may include the following:
- [Describe Dockerfile options](domain2/Describe_Dockerfile_options.md)
- [Show the main parts of a Dockerfile](domain2/Show_the_main_parts_of_a_Dockerfile.md)
- [Give examples on how to create an efficient image via a Dockerfile](domain2/Give_examples_on_how_to_create_an_efficient_image_via_a_Dockerfile.md)
- [Use CLI commands such as list delete prune rmi etc to manage images](domain2/Use_CLI_commands_such_as_list_delete_prune_rmi_etc_to_manage_images.md)
- [Inspect images and report specific attributes using filter and format](domain2/Inspect_images_and_report_specific_attributes_using_filter_and_format.md)
- [Demonstrate tagging an image](domain2/Demonstrate_tagging_an_image.md)
- [Utilize a registry to store an image](domain2/Utilize_a_registry_to_store_an_image.md)
- [Display layers of a Docker image](domain2/Display_layers_of_a_Docker_image.md)
- [Apply a file to create a Docker image](domain2/Apply_a_file_to_create_a_Docker_image.md)
- [Modify an image to a single layer](domain2/Modify_an_image_to_a_single_layer.md)
- [Describe how image layers work](domain2/Describe_how_image_layers_work.md)
- [Deploy a registry](domain2/Deploy_a_registry.md)
- [Configure a registry](domain2/Configure_a_registry.md)
- [Log into a registry](domain2/Log_into_a_registry.md)
- [Utilize search in a registry](domain2/Utilize_search_in_a_registry.md)
- [Tag an image](domain2/Tag_an_image.md)
- [Push an image to a registry](domain2/Push_an_image_to_a_registry.md)
- [Sign an image in a registry](domain2/Sign_an_image_in_a_registry.md)
- [Pull an image from a registry](domain2/Pull_an_image_from_a_registry.md)
- [Describe how image deletion works](domain2/Describe_how_image_deletion_works.md)
- [Delete an image from a registry](domain2/Delete_an_image_from_a_registry.md)

## Domain 3: Installation and Configuration (15% of exam)
Content may include the following:
- [Demonstrate the ability to upgrade the Docker engine](domain3/Demonstrate_the_ability_to_upgrade_the_Docker_engine.md)
- [Complete setup of repo select a storage driver and complete installation of Docker engine on multiple platforms](domain3/Complete_setup_of_repo_select_a_storage_driver_and_complete_installation_of_Docker_engine_on_multiple_platforms.md)
- [Configure logging drivers](domain3/Configure_logging_drivers.md)
- [Setup swarm configure managers add nodes and setup backup schedule](domain3/Setup_swarm_configure_managers_add_nodes_and_setup_backup_schedule.md)
- [Create and manager user and teams](domain3/Create_and_manager_user_and_teams.md)
- [Interpret errors to troubleshoot installation issues without assistance](domain3/Interpret_errors_to_troubleshoot_installation_issues_without_assistance.md)
- [Outline the sizing requirements prior to installation](domain3/Outline_the_sizing_requirements_prior_to_installation.md)
- [Understand namespaces cgroups and configuration of certificates](domain3/Understand_namespaces_cgroups_and_configuration_of_certificates.md)
- [Use certificate-based client-server authentication to ensure a Docker daemon has the rights to access images on a registry](domain3/Use_certificate-based_client-server_authentication_to_ensure_a_Docker_daemon_has_the_rights_to_access_images_on_a_registry.md)
- [Consistently repeat steps to deploy Docker engine UCP and DTR on AWS and on premises in an HA config](domain3/Consistently_repeat_steps_to_deploy_Docker_engine_UCP_and_DTR_on_AWS_and_on_premises_in_an_HA_config.md)
- [Complete configuration of backups for UCP and DTR](domain3/Complete_configuration_of_backups_for_UCP_and_DTR.md)
- [Configure the Docker daemon to start on boot](domain3/Configure_the_Docker_daemon_to_start_on_boot.md)

### Domain 4: Networking (15% of exam)
Content may include the following:
- [Create a Docker bridge network for a developer to use for their containers](domain4/Create_a_Docker_bridge_network_for_a_developer_to_use_for_their_containers.md)
- [Troubleshoot container and engine logs to understand a connectivity issue between containers](domain4/Troubleshoot_container_and_engine_logs_to_understand_a_connectivity_issue_between_containers.md)
- [Publish a port so that an application is accessible externally](domain4/Publish_a_port_so_that_an_application_is_accessible_externally.md)
- [Identify which IP and port a container is externally accessible on](domain4/Identify_which_IP_and_port_a_container_is_externally_accessible_on.md)
- [Describe the different types and use cases for the built-in network drivers](domain4/Describe_the_different_types_and_use_cases_for_the_built-in_network_drivers.md)
- [Understand the Container Network Model and how it interfaces with the Docker engine and network and IPAM drivers](domain4/Understand_the_Container_Network_Model_and_how_it_interfaces_with_the_Docker_engine_and_network_and_IPAM_drivers.md)
- [Configure Docker to use external DNS](domain4/Configure_Docker_to_use_external_DNS.md)
- [Use Docker to load balance HTTP HTTPs traffic to an application](domain4/Use_Docker_to_load_balance_HTTP_HTTPs_traffic_to_an_application.md)
- [Understand and describe the types of traffic that flow between the Docker engine registry and UCP controllers](domain4/Understand_and_describe_the_types_of_traffic_that_flow_between_the_Docker_engine_registry_and_UCP_controllers.md)
- [Deploy a service on a Docker overlay network](domain4/Deploy_a_service_on_a_Docker_overlay_network.md)
- [Describe the difference between host and ingress port publishing mode](domain4/Describe_the_difference_between_host_and_ingress_port_publishing_mode.md)

### Domain 5: Security (15% of exam)
Content may include the following:
- [Describe the process of signing an image](domain5/Describe_the_process_of_signing_an_image.md)
- [Demonstrate that an image passes a security scan](domain5/Demonstrate_that_an_image_passes_a_security_scan.md)
- [Enable Docker Content Trust](domain5/Enable_Docker_Content_Trust.md)
- [Configure RBAC in UCP](domain5/Configure_RBAC_in_UCP.md)
- [Integrate UCP with LDAP AD](domain5/Integrate_UCP_with_LDAP_AD.md)
- [Demonstrate creation of UCP client bundles](domain5/Demonstrate_creation_of_UCP_client_bundles.md)
- [Describe default engine security](domain5/Describe_default_engine_security.md)
- [Describe swarm default security](domain5/Describe_swarm_default_security.md)
- [Describe MTLS](domain5/Describe_MTLS.md)
- [Identity roles](domain5/Identity_roles.md)
- [Describe the difference between UCP workers and managers](domain5/Describe_the_difference_between_UCP_workers_and_managers.md)
- [Describe process to use external certificates with UCP and DTR](domain5/Describe_process_to_use_external_certificates_with_UCP_and_DTR.md)

### Domain 6: Storage and Volumes (10% of exam)
Content may include the following:
- [State which graph driver should be used on which OS](domain6/State_which_graph_driver_should_be_used_on_which_OS.md)
- [Demonstrate how to configure devicemapper](domain6/Demonstrate_how_to_configure_devicemapper.md)
- [Compare object storage to block storage and explain which one is preferable when available](domain6/Compare_object_storage_to_block_storage_and_explain_which_one_is_preferable_when_available.md)
- [Summarize how an application is composed of layers and where those layers reside on the filesystem](domain6/Summarize_how_an_application_is_composed_of_layers_and_where_those_layers_reside_on_the_filesystem.md)
- [Describe how volumes are used with Docker for persistent storage](domain6/Describe_how_volumes_are_used_with_Docker_for_persistent_storage.md)
- [Identify the steps you would take to clean up unused images on a filesystem also on DTR](domain6/Identify_the_steps_you_would_take_to_clean_up_unused_images_on_a_filesystem_also_on_DTR.md)
- [Demonstrate how storage can be used across cluster nodes](domain6/Demonstrate_how_storage_can_be_used_across_cluster_nodes.md)
