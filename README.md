# Server Metrics 2026-03-12 13:28:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 26991.4 (7h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 937488
telemt_connections_bad_total 5895
telemt_handshake_timeouts_total 8527
telemt_upstream_connect_attempt_total 5235
telemt_upstream_connect_success_total 5203
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 5235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2807
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 356
telemt_me_reconnect_attempts_total 7735
telemt_me_reconnect_success_total 3837
telemt_me_reader_eof_total 4118
telemt_me_idle_close_by_peer_total 4117
telemt_me_route_drop_no_conn_total 331649
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 895981
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4789
telemt_desync_full_logged_total 1211
telemt_desync_suppressed_total 3578
telemt_desync_frames_bucket_total{bucket="1_2"} 1198
telemt_desync_frames_bucket_total{bucket="3_10"} 1743
telemt_desync_frames_bucket_total{bucket="gt_10"} 1848
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 4002
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3824
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 895799
telemt_user_connections_current{user="hello"} 1527
telemt_user_octets_from_client{user="hello"} 14717293396 (13.71 GB)
telemt_user_octets_to_client{user="hello"} 268232199392 (249.81 GB)
telemt_user_unique_ips_current{user="hello"} 430
telemt_user_unique_ips_recent_window{user="hello"} 225
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 56612.0 (15h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 457343
telemt_connections_bad_total 5284
telemt_handshake_timeouts_total 24652
telemt_upstream_connect_attempt_total 13665
telemt_upstream_connect_success_total 13658
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 13665
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6716
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6926
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1109
telemt_me_reconnect_attempts_total 10723
telemt_me_reconnect_success_total 10664
telemt_me_reader_eof_total 11337
telemt_me_idle_close_by_peer_total 11337
telemt_me_route_drop_no_conn_total 131614
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 404343
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1369
telemt_desync_full_logged_total 446
telemt_desync_suppressed_total 923
telemt_desync_frames_bucket_total{bucket="1_2"} 559
telemt_desync_frames_bucket_total{bucket="3_10"} 470
telemt_desync_frames_bucket_total{bucket="gt_10"} 340
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 10762
telemt_me_writer_restored_same_endpoint_total 10655
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 404809
telemt_user_connections_current{user="hello"} 628
telemt_user_octets_from_client{user="hello"} 6322132615 (5.89 GB)
telemt_user_octets_to_client{user="hello"} 146728805326 (136.65 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 56611.9 (15h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1005433
telemt_connections_bad_total 5461
telemt_handshake_timeouts_total 75800
telemt_upstream_connect_attempt_total 13599
telemt_upstream_connect_success_total 13594
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 13599
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6133
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 917
telemt_me_reconnect_attempts_total 10516
telemt_me_reconnect_success_total 10422
telemt_me_reader_eof_total 10979
telemt_me_idle_close_by_peer_total 10979
telemt_me_route_drop_no_conn_total 255692
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 706017
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3067
telemt_desync_full_logged_total 930
telemt_desync_suppressed_total 2137
telemt_desync_frames_bucket_total{bucket="1_2"} 440
telemt_desync_frames_bucket_total{bucket="3_10"} 1102
telemt_desync_frames_bucket_total{bucket="gt_10"} 1525
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 10456
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 10381
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 706236
telemt_user_connections_current{user="hello"} 951
telemt_user_octets_from_client{user="hello"} 9295437360 (8.66 GB)
telemt_user_octets_to_client{user="hello"} 230120143393 (214.32 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 284
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 56612.4 (15h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 573866
telemt_connections_bad_total 7670
telemt_handshake_timeouts_total 53267
telemt_upstream_connect_attempt_total 15056
telemt_upstream_connect_success_total 14995
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 15056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8521
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6462
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 1301
telemt_me_reconnect_attempts_total 13413
telemt_me_reconnect_success_total 12180
telemt_me_reader_eof_total 12922
telemt_me_idle_close_by_peer_total 12922
telemt_me_route_drop_no_conn_total 192587
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 482048
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 976
telemt_desync_full_logged_total 343
telemt_desync_suppressed_total 633
telemt_desync_frames_bucket_total{bucket="1_2"} 278
telemt_desync_frames_bucket_total{bucket="3_10"} 401
telemt_desync_frames_bucket_total{bucket="gt_10"} 297
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12311
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 12159
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 131
telemt_user_connections_total{user="hello"} 481557
telemt_user_connections_current{user="hello"} 691
telemt_user_octets_from_client{user="hello"} 5418395568 (5.05 GB)
telemt_user_octets_to_client{user="hello"} 195545607080 (182.12 GB)
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 56612.3 (15h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 647751
telemt_connections_bad_total 1740
telemt_handshake_timeouts_total 5333
telemt_upstream_connect_attempt_total 17966
telemt_upstream_connect_success_total 17748
telemt_upstream_connect_fail_total 218
telemt_upstream_connect_attempts_per_request{bucket="1"} 17966
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9018
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8631
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 218
telemt_me_keepalive_timeout_total 1014
telemt_me_reconnect_attempts_total 22154
telemt_me_reconnect_success_total 14927
telemt_me_reader_eof_total 15656
telemt_me_idle_close_by_peer_total 15656
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 220573
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 602590
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2512
telemt_desync_full_logged_total 845
telemt_desync_suppressed_total 1667
telemt_desync_frames_bucket_total{bucket="1_2"} 694
telemt_desync_frames_bucket_total{bucket="3_10"} 886
telemt_desync_frames_bucket_total{bucket="gt_10"} 932
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 15299
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 14899
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 372
telemt_user_connections_total{user="hello"} 602500
telemt_user_connections_current{user="hello"} 824
telemt_user_octets_from_client{user="hello"} 6929325420 (6.45 GB)
telemt_user_octets_to_client{user="hello"} 160714380636 (149.68 GB)
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 122
```