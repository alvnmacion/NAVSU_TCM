# NAVSU Test Case Management Repository

This repository contains structured test cases for the **NAVSU Navigation App**.

All test cases follow a standardized format for easy tracking and review.

---

## [Account Creation and Authentication](./Authentication%20Testing)

- [AUTH-001_user_signup_successful](./Authentication%20Testing/AUTH-001_user_signup_successful.md)
- [AUTH-002_signup_existing_email](./Authentication%20Testing/AUTH-002_signup_existing_email.md)
- [AUTH-003_signup_invalid_email](./Authentication%20Testing/AUTH-003_signup_invalid_email.md)
- [AUTH-004_signup_weak_password](./Authentication%20Testing/AUTH-004_signup_weak_password.md)
- [AUTH-005_user_signin_successful](./Authentication%20Testing/AUTH-005_user_signin_successful.md)
- [AUTH-006_admin_signin_successful](./Authentication%20Testing/AUTH-006_admin_signin_successful.md)
- [AUTH-007_signin_incorrect_password](./Authentication%20Testing/AUTH-007_signin_incorrect_password.md)
- [AUTH-008_signin_nonexistent_email](./Authentication%20Testing/AUTH-008_signin_nonexistent_email.md)
- [AUTH-009_user_signout_successful](./Authentication%20Testing/AUTH-009_user_signout_successful.md)
- [AUTH-010_admin_signout_successful](./Authentication%20Testing/AUTH-010_admin_signout_successful.md)
- [AUTH-011_session_persistence](./Authentication%20Testing/AUTH-011_session_persistence.md)
- [AUTH-012_user_role_redirection](./Authentication%20Testing/AUTH-012_user_role_redirection.md)
- [AUTH-013_admin_role_redirection](./Authentication%20Testing/AUTH-013_admin_role_redirection.md)

---

## [Map and Navigation Testing](./Map%20and%20Navigation%20Testing)

- [MAP-001_map_display_initial](./Map%20and%20Navigation%20Testing/MAP-001_map_display_initial.md)
- [MAP-002_current_location](./Map%20and%20Navigation%20Testing/MAP-002_current_location.md)
- [MAP-003_current_location_button](./Map%20and%20Navigation%20Testing/MAP-003_current_location_button.md)
- [MAP-004_landmark_search_full_name](./Map%20and%20Navigation%20Testing/MAP-004_landmark_search_full_name.md)
- [MAP-005_landmark_search_partial](./Map%20and%20Navigation%20Testing/MAP-005_landmark_search_partial.md)
- [MAP-006_landmark_search_no_results](./Map%20and%20Navigation%20Testing/MAP-006_landmark_search_no_results.md)
- [MAP-007_landmark_selection](./Map%20and%20Navigation%20Testing/MAP-007_landmark_selection.md)
- [MAP-008_landmark_details_dialog](./Map%20and%20Navigation%20Testing/MAP-008_landmark_details_dialog.md)
- [MAP-009_route_calculation](./Map%20and%20Navigation%20Testing/MAP-009_route_calculation.md)
- [MAP-010_route_display](./Map%20and%20Navigation%20Testing/MAP-010_route_display.md)
- [MAP-011_navigation_start](./Map%20and%20Navigation%20Testing/MAP-011_navigation_start.md)
- [MAP-012_navigation_ui](./Map%20and%20Navigation%20Testing/MAP-012_navigation_ui.md)
- [MAP-013_navigation_updates](./Map%20and%20Navigation%20Testing/MAP-013_navigation_updates.md)
- [MAP-014_navigation_cancel](./Map%20and%20Navigation%20Testing/MAP-014_navigation_cancel.md)
- [MAP-015_arrival_detection](./Map%20and%20Navigation%20Testing/MAP-015_arrival_detection.md)
- [MAP-016_points_accumulation_navigation](./Map%20and%20Navigation%20Testing/MAP-016_points_accumulation_navigation.md)
- [MAP-017_points_accumulation_cancel](./Map%20and%20Navigation%20Testing/MAP-017_points_accumulation_cancel.md)
- [MAP-018_map_interaction](./Map%20and%20Navigation%20Testing/MAP-018_map_interaction.md)
- [MAP-019_location_permission](./Map%20and%20Navigation%20Testing/MAP-019_location_permission.md)
- [MAP-020_map_rotation](./Map%20and%20Navigation%20Testing/MAP-020_map_rotation.md)
- [MAP-021_hamburger_menu](./Map%20and%20Navigation%20Testing/MAP-021_hamburger_menu.md)
- [MAP-022_user_details_display](./Map%20and%20Navigation%20Testing/MAP-022_user_details_display.md)

---

## [Landmark Management (User) Testing](./Landmark%20Management%20Testing)

- [LMU-001_add_landmark_dialog](./Landmark%20Management%20Testing/LMU-001_add_landmark_dialog.md)
- [LMU-002_add_landmark_valid](./Landmark%20Management%20Testing/LMU-002_add_landmark_valid.md)
- [LMU-003_add_landmark_missing_fields](./Landmark%20Management%20Testing/LMU-003_add_landmark_missing_fields.md)
- [LMU-004_add_landmark_invalid_location](./Landmark%20Management%20Testing/LMU-004_add_landmark_invalid_location.md)
- [LMU-005_add_landmark_pending_status](./Landmark%20Management%20Testing/LMU-005_add_landmark_pending_status.md)

---

## [Rewards System (User) Testing](./Rewards%20System%20Testing)

- [REWU-001_view_rewards](./Rewards%20System%20Testing/REWU-001_view_rewards.md)
- [REWU-002_reward_details](./Rewards%20System%20Testing/REWU-002_reward_details.md)
- [REWU-003_redeem_reward_success](./Rewards%20System%20Testing/REWU-003_redeem_reward_success.md)
- [REWU-004_redeem_reward_insufficient_points](./Rewards%20System%20Testing/REWU-004_redeem_reward_insufficient_points.md)
- [REWU-005_redeem_reward_out_of_stock](./Rewards%20System%20Testing/REWU-005_redeem_reward_out_of_stock.md)
- [REWU-006_points_deduction](./Rewards%20System%20Testing/REWU-006_points_deduction.md)
- [REWU-007_redemption_confirmation_dialog](./Rewards%20System%20Testing/REWU-007_redemption_confirmation_dialog.md)
- [REWU-008_redemption_history](./Rewards%20System%20Testing/REWU-008_redemption_history.md)

---

## [Admin Panel - General Testing](./Admin%20Panel%20Testing)

- [ADM-001_admin_login](./Admin%20Panel%20Testing/ADM-001_admin_login.md)
- [ADM-002_admin_navigation](./Admin%20Panel%20Testing/ADM-002_admin_navigation.md)
- [ADM-003_admin_logout](./Admin%20Panel%20Testing/ADM-003_admin_logout.md)

---

## [Admin Panel - Landmark Approval Testing](./Admin%20Panel%20Testing)

- [ADML-001_view_pending_landmarks](./Admin%20Panel%20Testing/ADML-001_view_pending_landmarks.md)
- [ADML-002_approve_landmark](./Admin%20Panel%20Testing/ADML-002_approve_landmark.md)
- [ADML-003_reject_landmark](./Admin%20Panel%20Testing/ADML-003_reject_landmark.md)
- [ADML-004_delete_landmark](./Admin%20Panel%20Testing/ADML-004_delete_landmark.md)
- [ADML-005_view_landmark_details_admin](./Admin%20Panel%20Testing/ADML-005_view_landmark_details_admin.md)
- [ADML-006_landmark_list_sorting_filtering](./Admin%20Panel%20Testing/ADML-006_landmark_list_sorting_filtering.md)

---

## [Admin Panel - User Authorization Testing](./Admin%20Panel%20Testing)

- [ADMU-001_view_users_list](./Admin%20Panel%20Testing/ADMU-001_view_users_list.md)
- [ADMU-002_change_user_role](./Admin%20Panel%20Testing/ADMU-002_change_user_role.md)
- [ADMU-003_search_filter_users](./Admin%20Panel%20Testing/ADMU-003_search_filter_users.md)
- [ADMU-004_view_user_details_admin](./Admin%20Panel%20Testing/ADMU-004_view_user_details_admin.md)

---

## [Admin Panel - Rewards Management Testing](./Admin%20Panel%20Testing)

- [ADMR-001_add_reward](./Admin%20Panel%20Testing/ADMR-001_add_reward.md)
- [ADMR-002_edit_reward](./Admin%20Panel%20Testing/ADMR-002_edit_reward.md)
- [ADMR-003_delete_reward](./Admin%20Panel%20Testing/ADMR-003_delete_reward.md)
- [ADMR-004_view_rewards_list_admin](./Admin%20Panel%20Testing/ADMR-004_view_rewards_list_admin.md)
- [ADMR-005_reward_form_validation](./Admin%20Panel%20Testing/ADMR-005_reward_form_validation.md)

---

## [Admin Panel - Reward Redemption Approval Testing](./Admin%20Panel%20Testing)

- [ADMRA-001_view_pending_redemptions](./Admin%20Panel%20Testing/ADMRA-001_view_pending_redemptions.md)
- [ADMRA-002_approve_redemption](./Admin%20Panel%20Testing/ADMRA-002_approve_redemption.md)
- [ADMRA-003_reject_redemption](./Admin%20Panel%20Testing/ADMRA-003_reject_redemption.md)
- [ADMRA-004_view_redemption_details_admin](./Admin%20Panel%20Testing/ADMRA-004_view_redemption_details_admin.md)
- [ADMRA-005_empty_state](./Admin%20Panel%20Testing/ADMRA-005_empty_state.md)

---

## [User Interface (UI) & User Experience (UX) Testing](./UI%20UX%20Testing)

- [UIUX-001_app_startup_visuals](./UI%20UX%20Testing/UIUX-001_app_startup_visuals.md)
- [UIUX-002_visual_consistency](./UI%20UX%20Testing/UIUX-002_visual_consistency.md)
- [UIUX-003_responsiveness](./UI%20UX%20Testing/UIUX-003_responsiveness.md)
- [UIUX-004_navigation_flow](./UI%20UX%20Testing/UIUX-004_navigation_flow.md)
- [UIUX-005_loading_indicators](./UI%20UX%20Testing/UIUX-005_loading_indicators.md)
- [UIUX-006_error_handling_messages](./UI%20UX%20Testing/UIUX-006_error_handling_messages.md)
- [UIUX-007_dialogs](./UI%20UX%20Testing/UIUX-007_dialogs.md)
- [UIUX-008_input_fields_forms](./UI%20UX%20Testing/UIUX-008_input_fields_forms.md)
- [UIUX-009_snackbars_toasts](./UI%20UX%20Testing/UIUX-009_snackbars_toasts.md)
- [UIUX-010_image_handling](./UI%20UX%20Testing/UIUX-010_image_handling.md)
- [UIUX-011_text_overflow](./UI%20UX%20Testing/UIUX-011_text_overflow.md)

---

## [Performance Testing](./Performance%20Testing)

- [PERF-001_app_cold_start_time](./Performance%20Testing/PERF-001_app_cold_start_time.md)
- [PERF-002_map_rendering_interaction](./Performance%20Testing/PERF-002_map_rendering_interaction.md)
- [PERF-003_route_calculation_time](./Performance%20Testing/PERF-003_route_calculation_time.md)
- [PERF-004_data_fetching_times](./Performance%20Testing/PERF-004_data_fetching_times.md)
- [PERF-005_battery_consumption](./Performance%20Testing/PERF-005_battery_consumption.md)
- [PERF-006_memory_usage](./Performance%20Testing/PERF-006_memory_usage.md)
- [PERF-007_ui_responsiveness_under_load](./Performance%20Testing/PERF-007_ui_responsiveness_under_load.md)

---

## [Connectivity Testing](./Connectivity%20Testing)

- [CONN-001_offline_startup](./Connectivity%20Testing/CONN-001_offline_startup.md)
- [CONN-002_network_interruption_navigation](./Connectivity%20Testing/CONN-002_network_interruption_navigation.md)
- [CONN-003_network_interruption_data_fetch](./Connectivity%20Testing/CONN-003_network_interruption_data_fetch.md)
- [CONN-004_network_restore](./Connectivity%20Testing/CONN-004_network_restore.md)
- [CONN-005_slow_network_performance](./Connectivity%20Testing/CONN-005_slow_network_performance.md)
- [CONN-006_cached_data_usage](./Connectivity%20Testing/CONN-006_cached_data_usage.md)

---

## [Security Testing](./Security%20Testing)

- [SEC-001_data_transmission_security](./Security%20Testing/SEC-001_data_transmission_security.md)
- [SEC-002_input_validation](./Security%20Testing/SEC-002_input_validation.md)
- [SEC-003_role_based_access_control](./Security%20Testing/SEC-003_role_based_access_control.md)
- [SEC-004_api_key_security](./Security%20Testing/SEC-004_api_key_security.md)
- [SEC-005_local_data_storage_security](./Security%20Testing/SEC-005_local_data_storage_security.md)
- [SEC-006_authentication_robustness](./Security%20Testing/SEC-006_authentication_robustness.md)
- [SEC-007_firestore_security_rules](./Security%20Testing/SEC-007_firestore_security_rules.md)

---

## [Platform Compatibility Testing (Basic Flutter Coverage)](./Platform%20Compatibility%20Testing)

- [PLAT-001_android_version_compatibility](./Platform%20Compatibility%20Testing/PLAT-001_android_version_compatibility.md)
- [PLAT-002_device_variety](./Platform%20Compatibility%20Testing/PLAT-003_device_variety.md)

---

## Test Coverage

See [test_coverage.md](./test_coverage.md) for a summary of coverage.
