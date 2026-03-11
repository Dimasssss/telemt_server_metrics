# Server Metrics 2026-03-11 17:55:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 98895.4 (27h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2502209
telemt_connections_bad_total 47558
telemt_handshake_timeouts_total 55769
telemt_upstream_connect_attempt_total 20799
telemt_upstream_connect_success_total 20787
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 20799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10492
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10195
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5239
telemt_me_reconnect_attempts_total 33673
telemt_me_reconnect_success_total 15793
telemt_me_reader_eof_total 17095
telemt_me_idle_close_by_peer_total 17095
telemt_me_route_drop_no_conn_total 930858
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2288301
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11758
telemt_desync_full_logged_total 3232
telemt_desync_suppressed_total 8526
telemt_desync_frames_bucket_total{bucket="1_2"} 2899
telemt_desync_frames_bucket_total{bucket="3_10"} 4546
telemt_desync_frames_bucket_total{bucket="gt_10"} 4313
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 16530
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 15787
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 737
telemt_user_connections_total{user="hello"} 2286746
telemt_user_connections_current{user="hello"} 1261
telemt_user_octets_from_client{user="hello"} 31247112524 (29.10 GB)
telemt_user_octets_to_client{user="hello"} 646598608108 (602.19 GB)
telemt_user_unique_ips_current{user="hello"} 349
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 98952.2 (27h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 940327
telemt_connections_bad_total 16343
telemt_handshake_timeouts_total 83711
telemt_upstream_connect_attempt_total 30943
telemt_upstream_connect_success_total 27979
telemt_upstream_connect_fail_total 2964
telemt_upstream_connect_attempts_per_request{bucket="1"} 30943
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12557
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2040
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2964
telemt_me_keepalive_timeout_total 2762
telemt_me_reconnect_attempts_total 22174
telemt_me_reconnect_success_total 20066
telemt_me_reader_eof_total 21234
telemt_me_idle_close_by_peer_total 21231
telemt_me_route_drop_no_conn_total 355095
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 783175
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3088
telemt_desync_full_logged_total 987
telemt_desync_suppressed_total 2101
telemt_desync_frames_bucket_total{bucket="1_2"} 944
telemt_desync_frames_bucket_total{bucket="3_10"} 1106
telemt_desync_frames_bucket_total{bucket="gt_10"} 1038
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 20345
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 20043
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 279
telemt_user_connections_total{user="hello"} 785637
telemt_user_connections_current{user="hello"} 514
telemt_user_octets_from_client{user="hello"} 9483332082 (8.83 GB)
telemt_user_octets_to_client{user="hello"} 222185679196 (206.93 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 98952.3 (27h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1605700
telemt_connections_bad_total 9991
telemt_handshake_timeouts_total 129998
telemt_upstream_connect_attempt_total 25594
telemt_upstream_connect_success_total 25272
telemt_upstream_connect_fail_total 322
telemt_upstream_connect_attempts_per_request{bucket="1"} 25594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13590
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11554
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 127
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 322
telemt_me_keepalive_timeout_total 1896
telemt_me_reconnect_attempts_total 45218
telemt_me_reconnect_success_total 19214
telemt_me_reader_eof_total 20873
telemt_me_idle_close_by_peer_total 20873
telemt_me_route_drop_no_conn_total 584322
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1404226
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3785
telemt_desync_full_logged_total 1102
telemt_desync_suppressed_total 2683
telemt_desync_frames_bucket_total{bucket="1_2"} 905
telemt_desync_frames_bucket_total{bucket="3_10"} 1442
telemt_desync_frames_bucket_total{bucket="gt_10"} 1438
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 20292
telemt_me_refill_failed_total 807
telemt_me_writer_restored_same_endpoint_total 19202
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1078
telemt_user_connections_total{user="hello"} 1403913
telemt_user_connections_current{user="hello"} 780
telemt_user_octets_from_client{user="hello"} 17349322013 (16.16 GB)
telemt_user_octets_to_client{user="hello"} 427278204729 (397.93 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 229
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 98952.5 (27h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1146300
telemt_connections_bad_total 77991
telemt_handshake_timeouts_total 107491
telemt_upstream_connect_attempt_total 26720
telemt_upstream_connect_success_total 26720
telemt_upstream_connect_attempts_per_request{bucket="1"} 26720
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14573
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12141
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1276
telemt_me_reconnect_attempts_total 25143
telemt_me_reconnect_success_total 21786
telemt_me_reader_eof_total 23110
telemt_me_idle_close_by_peer_total 23109
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 380363
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 926941
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1938
telemt_desync_full_logged_total 744
telemt_desync_suppressed_total 1194
telemt_desync_frames_bucket_total{bucket="1_2"} 689
telemt_desync_frames_bucket_total{bucket="3_10"} 676
telemt_desync_frames_bucket_total{bucket="gt_10"} 573
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 22123
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 21753
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 337
telemt_user_connections_total{user="hello"} 926218
telemt_user_connections_current{user="hello"} 491
telemt_user_octets_from_client{user="hello"} 11155612468 (10.39 GB)
telemt_user_octets_to_client{user="hello"} 282118112892 (262.74 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 3628.9 (1h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64759
telemt_connections_bad_total 315
telemt_handshake_timeouts_total 379
telemt_upstream_connect_attempt_total 1108
telemt_upstream_connect_success_total 1108
telemt_upstream_connect_attempts_per_request{bucket="1"} 1108
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 635
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 461
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 905
telemt_me_reconnect_success_total 898
telemt_me_reader_eof_total 878
telemt_me_idle_close_by_peer_total 878
telemt_me_route_drop_no_conn_total 21668
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60701
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 146
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 98
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 64
telemt_me_writer_removed_unexpected_total 901
telemt_me_writer_restored_same_endpoint_total 876
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 60698
telemt_user_connections_current{user="hello"} 700
telemt_user_octets_from_client{user="hello"} 5873723588 (5.47 GB)
telemt_user_octets_to_client{user="hello"} 22462533684 (20.92 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 99
```