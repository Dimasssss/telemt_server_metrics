# Server Metrics 2026-03-12 15:36:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 34646.0 (9h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1246395
telemt_connections_bad_total 20234
telemt_handshake_timeouts_total 12400
telemt_upstream_connect_attempt_total 6982
telemt_upstream_connect_success_total 6945
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 6982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3717
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3214
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 417
telemt_me_reconnect_attempts_total 9082
telemt_me_reconnect_success_total 5176
telemt_me_reader_eof_total 5516
telemt_me_idle_close_by_peer_total 5515
telemt_me_route_drop_no_conn_total 444442
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1173013
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6212
telemt_desync_full_logged_total 1548
telemt_desync_suppressed_total 4664
telemt_desync_frames_bucket_total{bucket="1_2"} 1596
telemt_desync_frames_bucket_total{bucket="3_10"} 2229
telemt_desync_frames_bucket_total{bucket="gt_10"} 2387
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 5360
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 5163
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 1172702
telemt_user_connections_current{user="hello"} 1561
telemt_user_octets_from_client{user="hello"} 18261641364 (17.01 GB)
telemt_user_octets_to_client{user="hello"} 340982497100 (317.56 GB)
telemt_user_unique_ips_current{user="hello"} 430
telemt_user_unique_ips_recent_window{user="hello"} 229
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 64266.4 (17h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 561285
telemt_connections_bad_total 6926
telemt_handshake_timeouts_total 27399
telemt_upstream_connect_attempt_total 15476
telemt_upstream_connect_success_total 15469
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 15476
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7691
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7762
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1179
telemt_me_reconnect_attempts_total 12136
telemt_me_reconnect_success_total 12069
telemt_me_reader_eof_total 12827
telemt_me_idle_close_by_peer_total 12827
telemt_me_route_drop_no_conn_total 165099
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 501123
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1932
telemt_desync_full_logged_total 612
telemt_desync_suppressed_total 1320
telemt_desync_frames_bucket_total{bucket="1_2"} 852
telemt_desync_frames_bucket_total{bucket="3_10"} 617
telemt_desync_frames_bucket_total{bucket="gt_10"} 463
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 12186
telemt_me_writer_restored_same_endpoint_total 12060
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 501620
telemt_user_connections_current{user="hello"} 545
telemt_user_octets_from_client{user="hello"} 7799916895 (7.26 GB)
telemt_user_octets_to_client{user="hello"} 177798576038 (165.59 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 64266.5 (17h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1193676
telemt_connections_bad_total 6163
telemt_handshake_timeouts_total 83018
telemt_upstream_connect_attempt_total 15513
telemt_upstream_connect_success_total 15507
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 15512
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8381
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7061
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 990
telemt_me_reconnect_attempts_total 13153
telemt_me_reconnect_success_total 11929
telemt_me_reader_eof_total 12584
telemt_me_idle_close_by_peer_total 12584
telemt_me_route_drop_no_conn_total 321622
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 879723
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3704
telemt_desync_full_logged_total 1136
telemt_desync_suppressed_total 2568
telemt_desync_frames_bucket_total{bucket="1_2"} 561
telemt_desync_frames_bucket_total{bucket="3_10"} 1346
telemt_desync_frames_bucket_total{bucket="gt_10"} 1797
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 12016
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 11888
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 879906
telemt_user_connections_current{user="hello"} 911
telemt_user_octets_from_client{user="hello"} 11702508844 (10.90 GB)
telemt_user_octets_to_client{user="hello"} 276176640261 (257.21 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 64266.9 (17h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 708043
telemt_connections_bad_total 7701
telemt_handshake_timeouts_total 57968
telemt_upstream_connect_attempt_total 16973
telemt_upstream_connect_success_total 16904
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 16973
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9599
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7292
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 1368
telemt_me_reconnect_attempts_total 18922
telemt_me_reconnect_success_total 13681
telemt_me_reader_eof_total 14592
telemt_me_idle_close_by_peer_total 14592
telemt_me_route_drop_no_conn_total 240704
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 608243
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1235
telemt_desync_full_logged_total 421
telemt_desync_suppressed_total 814
telemt_desync_frames_bucket_total{bucket="1_2"} 330
telemt_desync_frames_bucket_total{bucket="3_10"} 493
telemt_desync_frames_bucket_total{bucket="gt_10"} 412
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 13948
telemt_me_refill_failed_total 162
telemt_me_writer_restored_same_endpoint_total 13660
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 267
telemt_user_connections_total{user="hello"} 607730
telemt_user_connections_current{user="hello"} 561
telemt_user_octets_from_client{user="hello"} 7649869084 (7.12 GB)
telemt_user_octets_to_client{user="hello"} 239936157604 (223.46 GB)
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 64266.6 (17h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 798356
telemt_connections_bad_total 7969
telemt_handshake_timeouts_total 6261
telemt_upstream_connect_attempt_total 20428
telemt_upstream_connect_success_total 20176
telemt_upstream_connect_fail_total 252
telemt_upstream_connect_attempts_per_request{bucket="1"} 20428
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9823
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 252
telemt_me_keepalive_timeout_total 1121
telemt_me_reconnect_attempts_total 24189
telemt_me_reconnect_success_total 16952
telemt_me_reader_eof_total 17758
telemt_me_idle_close_by_peer_total 17758
telemt_me_seq_mismatch_total 27
telemt_me_route_drop_no_conn_total 279587
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 737252
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 31
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2912
telemt_desync_full_logged_total 985
telemt_desync_suppressed_total 1927
telemt_desync_frames_bucket_total{bucket="1_2"} 822
telemt_desync_frames_bucket_total{bucket="3_10"} 992
telemt_desync_frames_bucket_total{bucket="gt_10"} 1098
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 17353
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 16918
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 401
telemt_user_connections_total{user="hello"} 737149
telemt_user_connections_current{user="hello"} 843
telemt_user_octets_from_client{user="hello"} 8849650992 (8.24 GB)
telemt_user_octets_to_client{user="hello"} 207324604064 (193.09 GB)
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 109
```