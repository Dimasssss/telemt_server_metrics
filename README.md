# Server Metrics 2026-03-12 18:45:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 45988.1 (12h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1640920
telemt_connections_bad_total 20513
telemt_handshake_timeouts_total 15138
telemt_upstream_connect_attempt_total 9132
telemt_upstream_connect_success_total 9080
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 9132
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4754
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4296
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 568
telemt_me_reconnect_attempts_total 15571
telemt_me_reconnect_success_total 6725
telemt_me_reader_eof_total 7280
telemt_me_idle_close_by_peer_total 7279
telemt_me_route_drop_no_conn_total 642672
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1536661
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7853
telemt_desync_full_logged_total 1992
telemt_desync_suppressed_total 5861
telemt_desync_frames_bucket_total{bucket="1_2"} 2038
telemt_desync_frames_bucket_total{bucket="3_10"} 2844
telemt_desync_frames_bucket_total{bucket="gt_10"} 2971
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 7095
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 6712
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 370
telemt_user_connections_total{user="hello"} 1536147
telemt_user_connections_current{user="hello"} 1382
telemt_user_octets_from_client{user="hello"} 23750744340 (22.12 GB)
telemt_user_octets_to_client{user="hello"} 518369958036 (482.77 GB)
telemt_user_unique_ips_current{user="hello"} 391
telemt_user_unique_ips_recent_window{user="hello"} 187
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 75608.6 (21h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 704883
telemt_connections_bad_total 9238
telemt_handshake_timeouts_total 29482
telemt_upstream_connect_attempt_total 19312
telemt_upstream_connect_success_total 19283
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 19312
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8991
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3366
telemt_me_reconnect_attempts_total 13945
telemt_me_reconnect_success_total 13860
telemt_me_reader_eof_total 14733
telemt_me_idle_close_by_peer_total 14733
telemt_me_route_drop_no_conn_total 225043
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 634757
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2784
telemt_desync_full_logged_total 855
telemt_desync_suppressed_total 1929
telemt_desync_frames_bucket_total{bucket="1_2"} 1105
telemt_desync_frames_bucket_total{bucket="3_10"} 912
telemt_desync_frames_bucket_total{bucket="gt_10"} 767
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 14007
telemt_me_writer_restored_same_endpoint_total 13851
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 636637
telemt_user_connections_current{user="hello"} 529
telemt_user_octets_from_client{user="hello"} 9730373664 (9.06 GB)
telemt_user_octets_to_client{user="hello"} 239461467683 (223.02 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 75608.6 (21h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1459543
telemt_connections_bad_total 6998
telemt_handshake_timeouts_total 100796
telemt_upstream_connect_attempt_total 17956
telemt_upstream_connect_success_total 17951
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 17956
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9649
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8230
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1183
telemt_me_reconnect_attempts_total 15056
telemt_me_reconnect_success_total 13812
telemt_me_reader_eof_total 14562
telemt_me_idle_close_by_peer_total 14561
telemt_me_route_drop_no_conn_total 481145
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1115783
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4705
telemt_desync_full_logged_total 1449
telemt_desync_suppressed_total 3256
telemt_desync_frames_bucket_total{bucket="1_2"} 736
telemt_desync_frames_bucket_total{bucket="3_10"} 1705
telemt_desync_frames_bucket_total{bucket="gt_10"} 2264
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 13937
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 13771
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 1115646
telemt_user_connections_current{user="hello"} 841
telemt_user_octets_from_client{user="hello"} 17575944824 (16.37 GB)
telemt_user_octets_to_client{user="hello"} 405831904013 (377.96 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 245
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 75609.2 (21h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 890740
telemt_connections_bad_total 12713
telemt_handshake_timeouts_total 65798
telemt_upstream_connect_attempt_total 19540
telemt_upstream_connect_success_total 19464
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 19540
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10953
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8498
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 1627
telemt_me_reconnect_attempts_total 23416
telemt_me_reconnect_success_total 15692
telemt_me_reader_eof_total 16758
telemt_me_idle_close_by_peer_total 16758
telemt_me_route_drop_no_conn_total 313891
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 770049
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1736
telemt_desync_full_logged_total 582
telemt_desync_suppressed_total 1154
telemt_desync_frames_bucket_total{bucket="1_2"} 487
telemt_desync_frames_bucket_total{bucket="3_10"} 674
telemt_desync_frames_bucket_total{bucket="gt_10"} 575
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 16059
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 15671
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 367
telemt_user_connections_total{user="hello"} 769410
telemt_user_connections_current{user="hello"} 552
telemt_user_octets_from_client{user="hello"} 9360080824 (8.72 GB)
telemt_user_octets_to_client{user="hello"} 316497201424 (294.76 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 75608.7 (21h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 997631
telemt_connections_bad_total 11476
telemt_handshake_timeouts_total 8232
telemt_upstream_connect_attempt_total 23666
telemt_upstream_connect_success_total 23385
telemt_upstream_connect_fail_total 281
telemt_upstream_connect_attempts_per_request{bucket="1"} 23666
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11969
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11289
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 281
telemt_me_keepalive_timeout_total 1385
telemt_me_reconnect_attempts_total 30630
telemt_me_reconnect_success_total 19596
telemt_me_reader_eof_total 20597
telemt_me_idle_close_by_peer_total 20597
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 371095
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 915746
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3489
telemt_desync_full_logged_total 1212
telemt_desync_suppressed_total 2277
telemt_desync_frames_bucket_total{bucket="1_2"} 978
telemt_desync_frames_bucket_total{bucket="3_10"} 1169
telemt_desync_frames_bucket_total{bucket="gt_10"} 1342
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 20162
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 19552
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 566
telemt_user_connections_total{user="hello"} 915619
telemt_user_connections_current{user="hello"} 716
telemt_user_octets_from_client{user="hello"} 11333767796 (10.56 GB)
telemt_user_octets_to_client{user="hello"} 306391792464 (285.35 GB)
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 100
```