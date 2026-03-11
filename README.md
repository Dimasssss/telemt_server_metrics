# Server Metrics 2026-03-11 07:53:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 62762.7 (17h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1274340
telemt_connections_bad_total 13656
telemt_handshake_timeouts_total 39535
telemt_upstream_connect_attempt_total 13041
telemt_upstream_connect_success_total 13032
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 13041
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6558
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6411
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 719
telemt_me_reconnect_attempts_total 21549
telemt_me_reconnect_success_total 9864
telemt_me_reader_eof_total 10715
telemt_me_idle_close_by_peer_total 10715
telemt_me_route_drop_no_conn_total 469233
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1152661
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5670
telemt_desync_full_logged_total 1576
telemt_desync_suppressed_total 4094
telemt_desync_frames_bucket_total{bucket="1_2"} 1494
telemt_desync_frames_bucket_total{bucket="3_10"} 2152
telemt_desync_frames_bucket_total{bucket="gt_10"} 2024
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 10326
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 9858
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 462
telemt_user_connections_total{user="hello"} 1152316
telemt_user_connections_current{user="hello"} 1214
telemt_user_octets_from_client{user="hello"} 15090052500 (14.05 GB)
telemt_user_octets_to_client{user="hello"} 337979548048 (314.77 GB)
telemt_user_unique_ips_current{user="hello"} 330
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 62819.5 (17h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 495428
telemt_connections_bad_total 7344
telemt_handshake_timeouts_total 28337
telemt_upstream_connect_attempt_total 21959
telemt_upstream_connect_success_total 19040
telemt_upstream_connect_fail_total 2919
telemt_upstream_connect_attempts_per_request{bucket="1"} 21959
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8594
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8203
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2919
telemt_me_keepalive_timeout_total 2047
telemt_me_reconnect_attempts_total 13784
telemt_me_reconnect_success_total 12957
telemt_me_reader_eof_total 13708
telemt_me_idle_close_by_peer_total 13706
telemt_me_route_drop_no_conn_total 213509
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 419894
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2091
telemt_desync_full_logged_total 641
telemt_desync_suppressed_total 1450
telemt_desync_frames_bucket_total{bucket="1_2"} 684
telemt_desync_frames_bucket_total{bucket="3_10"} 753
telemt_desync_frames_bucket_total{bucket="gt_10"} 654
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 13105
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 12935
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 148
telemt_user_connections_total{user="hello"} 422162
telemt_user_connections_current{user="hello"} 452
telemt_user_octets_from_client{user="hello"} 4137103366 (3.85 GB)
telemt_user_octets_to_client{user="hello"} 111652927024 (103.98 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 62819.4 (17h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 830837
telemt_connections_bad_total 6912
telemt_handshake_timeouts_total 45056
telemt_upstream_connect_attempt_total 16993
telemt_upstream_connect_success_total 16783
telemt_upstream_connect_fail_total 210
telemt_upstream_connect_attempts_per_request{bucket="1"} 16993
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9137
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7558
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 210
telemt_me_keepalive_timeout_total 743
telemt_me_reconnect_attempts_total 24926
telemt_me_reconnect_success_total 12569
telemt_me_reader_eof_total 13533
telemt_me_idle_close_by_peer_total 13533
telemt_me_route_drop_no_conn_total 282336
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 743839
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2145
telemt_desync_full_logged_total 631
telemt_desync_suppressed_total 1514
telemt_desync_frames_bucket_total{bucket="1_2"} 499
telemt_desync_frames_bucket_total{bucket="3_10"} 779
telemt_desync_frames_bucket_total{bucket="gt_10"} 867
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 13114
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 12558
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 545
telemt_user_connections_total{user="hello"} 744630
telemt_user_connections_current{user="hello"} 754
telemt_user_octets_from_client{user="hello"} 8715874873 (8.12 GB)
telemt_user_octets_to_client{user="hello"} 222445022761 (207.17 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 62819.9 (17h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 634773
telemt_connections_bad_total 58815
telemt_handshake_timeouts_total 62646
telemt_upstream_connect_attempt_total 17558
telemt_upstream_connect_success_total 17558
telemt_upstream_connect_attempts_per_request{bucket="1"} 17558
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9813
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7741
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 664
telemt_me_reconnect_attempts_total 15475
telemt_me_reconnect_success_total 14423
telemt_me_reader_eof_total 15321
telemt_me_idle_close_by_peer_total 15320
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 195057
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 492654
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1160
telemt_desync_full_logged_total 446
telemt_desync_suppressed_total 714
telemt_desync_frames_bucket_total{bucket="1_2"} 393
telemt_desync_frames_bucket_total{bucket="3_10"} 432
telemt_desync_frames_bucket_total{bucket="gt_10"} 335
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 14593
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 14401
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 492052
telemt_user_connections_current{user="hello"} 452
telemt_user_octets_from_client{user="hello"} 5886932232 (5.48 GB)
telemt_user_octets_to_client{user="hello"} 134767387488 (125.51 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 62819.5 (17h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 664826
telemt_connections_bad_total 5975
telemt_handshake_timeouts_total 5238
telemt_upstream_connect_attempt_total 17412
telemt_upstream_connect_success_total 17340
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 17412
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8912
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8290
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 694
telemt_me_reconnect_attempts_total 17880
telemt_me_reconnect_success_total 14092
telemt_me_reader_eof_total 14898
telemt_me_idle_close_by_peer_total 14898
telemt_me_route_drop_no_conn_total 222932
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 606064
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2772
telemt_desync_full_logged_total 1047
telemt_desync_suppressed_total 1725
telemt_desync_frames_bucket_total{bucket="1_2"} 977
telemt_desync_frames_bucket_total{bucket="3_10"} 1158
telemt_desync_frames_bucket_total{bucket="gt_10"} 637
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 14389
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 14092
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 297
telemt_user_connections_total{user="hello"} 605770
telemt_user_connections_current{user="hello"} 650
telemt_user_octets_from_client{user="hello"} 10108961695 (9.41 GB)
telemt_user_octets_to_client{user="hello"} 220941589666 (205.77 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 112
```