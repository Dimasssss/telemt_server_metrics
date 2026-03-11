# Server Metrics 2026-03-11 18:05:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 99509.8 (27h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2520851
telemt_connections_bad_total 47969
telemt_handshake_timeouts_total 56208
telemt_upstream_connect_attempt_total 21013
telemt_upstream_connect_success_total 21001
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 21013
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10287
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5253
telemt_me_reconnect_attempts_total 33841
telemt_me_reconnect_success_total 15961
telemt_me_reader_eof_total 17263
telemt_me_idle_close_by_peer_total 17263
telemt_me_route_drop_no_conn_total 939158
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2305660
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11791
telemt_desync_full_logged_total 3245
telemt_desync_suppressed_total 8546
telemt_desync_frames_bucket_total{bucket="1_2"} 2912
telemt_desync_frames_bucket_total{bucket="3_10"} 4558
telemt_desync_frames_bucket_total{bucket="gt_10"} 4321
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 16699
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 15955
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 738
telemt_user_connections_total{user="hello"} 2304103
telemt_user_connections_current{user="hello"} 1228
telemt_user_octets_from_client{user="hello"} 31508836468 (29.34 GB)
telemt_user_octets_to_client{user="hello"} 651278594776 (606.55 GB)
telemt_user_unique_ips_current{user="hello"} 363
telemt_user_unique_ips_recent_window{user="hello"} 203
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 99566.6 (27h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 946098
telemt_connections_bad_total 16357
telemt_handshake_timeouts_total 84291
telemt_upstream_connect_attempt_total 31081
telemt_upstream_connect_success_total 28115
telemt_upstream_connect_fail_total 2966
telemt_upstream_connect_attempts_per_request{bucket="1"} 31081
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12620
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2040
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2966
telemt_me_keepalive_timeout_total 2768
telemt_me_reconnect_attempts_total 22267
telemt_me_reconnect_success_total 20157
telemt_me_reader_eof_total 21332
telemt_me_idle_close_by_peer_total 21329
telemt_me_route_drop_no_conn_total 357412
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 788264
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3102
telemt_desync_full_logged_total 995
telemt_desync_suppressed_total 2107
telemt_desync_frames_bucket_total{bucket="1_2"} 956
telemt_desync_frames_bucket_total{bucket="3_10"} 1107
telemt_desync_frames_bucket_total{bucket="gt_10"} 1039
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 20437
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 20134
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 280
telemt_user_connections_total{user="hello"} 790726
telemt_user_connections_current{user="hello"} 436
telemt_user_octets_from_client{user="hello"} 9552908518 (8.90 GB)
telemt_user_octets_to_client{user="hello"} 224502135148 (209.08 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 99566.4 (27h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1616406
telemt_connections_bad_total 9993
telemt_handshake_timeouts_total 130075
telemt_upstream_connect_attempt_total 25782
telemt_upstream_connect_success_total 25458
telemt_upstream_connect_fail_total 324
telemt_upstream_connect_attempts_per_request{bucket="1"} 25782
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11629
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 127
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 324
telemt_me_keepalive_timeout_total 1928
telemt_me_reconnect_attempts_total 45360
telemt_me_reconnect_success_total 19355
telemt_me_reader_eof_total 21017
telemt_me_idle_close_by_peer_total 21017
telemt_me_route_drop_no_conn_total 589183
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1414602
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3834
telemt_desync_full_logged_total 1122
telemt_desync_suppressed_total 2712
telemt_desync_frames_bucket_total{bucket="1_2"} 913
telemt_desync_frames_bucket_total{bucket="3_10"} 1459
telemt_desync_frames_bucket_total{bucket="gt_10"} 1462
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 20436
telemt_me_refill_failed_total 807
telemt_me_writer_restored_same_endpoint_total 19343
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1081
telemt_user_connections_total{user="hello"} 1414287
telemt_user_connections_current{user="hello"} 762
telemt_user_octets_from_client{user="hello"} 17497699773 (16.30 GB)
telemt_user_octets_to_client{user="hello"} 430642671773 (401.07 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 99567.0 (27h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1154439
telemt_connections_bad_total 77991
telemt_handshake_timeouts_total 107594
telemt_upstream_connect_attempt_total 26876
telemt_upstream_connect_success_total 26876
telemt_upstream_connect_attempts_per_request{bucket="1"} 26876
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14661
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12209
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1293
telemt_me_reconnect_attempts_total 26502
telemt_me_reconnect_success_total 21897
telemt_me_reader_eof_total 23260
telemt_me_idle_close_by_peer_total 23259
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 383959
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 934852
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1980
telemt_desync_full_logged_total 756
telemt_desync_suppressed_total 1224
telemt_desync_frames_bucket_total{bucket="1_2"} 712
telemt_desync_frames_bucket_total{bucket="3_10"} 685
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 22273
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 21864
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 376
telemt_user_connections_total{user="hello"} 934128
telemt_user_connections_current{user="hello"} 501
telemt_user_octets_from_client{user="hello"} 11217177772 (10.45 GB)
telemt_user_octets_to_client{user="hello"} 283931449980 (264.43 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 4243.0 (1h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75751
telemt_connections_bad_total 315
telemt_handshake_timeouts_total 451
telemt_upstream_connect_attempt_total 1269
telemt_upstream_connect_success_total 1269
telemt_upstream_connect_attempts_per_request{bucket="1"} 1269
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 716
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 541
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 1023
telemt_me_reconnect_success_total 1015
telemt_me_reader_eof_total 1023
telemt_me_idle_close_by_peer_total 1023
telemt_me_route_drop_no_conn_total 25152
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 71008
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 171
telemt_desync_full_logged_total 54
telemt_desync_suppressed_total 117
telemt_desync_frames_bucket_total{bucket="1_2"} 39
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1021
telemt_me_writer_restored_same_endpoint_total 993
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 71003
telemt_user_connections_current{user="hello"} 791
telemt_user_octets_from_client{user="hello"} 6016755728 (5.60 GB)
telemt_user_octets_to_client{user="hello"} 26462739724 (24.65 GB)
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 125
```