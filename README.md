# Server Metrics 2026-03-11 11:47:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 76834.9 (21h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1740983
telemt_connections_bad_total 25372
telemt_handshake_timeouts_total 44901
telemt_upstream_connect_attempt_total 16047
telemt_upstream_connect_success_total 16038
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 16047
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8071
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7898
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 827
telemt_me_reconnect_attempts_total 24967
telemt_me_reconnect_success_total 12146
telemt_me_reader_eof_total 13142
telemt_me_idle_close_by_peer_total 13142
telemt_me_route_drop_no_conn_total 640125
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1584999
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8353
telemt_desync_full_logged_total 2249
telemt_desync_suppressed_total 6104
telemt_desync_frames_bucket_total{bucket="1_2"} 2098
telemt_desync_frames_bucket_total{bucket="3_10"} 3196
telemt_desync_frames_bucket_total{bucket="gt_10"} 3059
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 12672
telemt_me_refill_failed_total 398
telemt_me_writer_restored_same_endpoint_total 12140
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 526
telemt_user_connections_total{user="hello"} 1583560
telemt_user_connections_current{user="hello"} 1444
telemt_user_octets_from_client{user="hello"} 20473725732 (19.07 GB)
telemt_user_octets_to_client{user="hello"} 451462867392 (420.46 GB)
telemt_user_unique_ips_current{user="hello"} 366
telemt_user_unique_ips_recent_window{user="hello"} 217
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 76891.7 (21h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 658009
telemt_connections_bad_total 11627
telemt_handshake_timeouts_total 41350
telemt_upstream_connect_attempt_total 25204
telemt_upstream_connect_success_total 22265
telemt_upstream_connect_fail_total 2939
telemt_upstream_connect_attempts_per_request{bucket="1"} 25204
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9808
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2939
telemt_me_keepalive_timeout_total 2191
telemt_me_reconnect_attempts_total 16310
telemt_me_reconnect_success_total 15459
telemt_me_reader_eof_total 16354
telemt_me_idle_close_by_peer_total 16352
telemt_me_route_drop_no_conn_total 265646
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 557929
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2544
telemt_desync_full_logged_total 802
telemt_desync_suppressed_total 1742
telemt_desync_frames_bucket_total{bucket="1_2"} 825
telemt_desync_frames_bucket_total{bucket="3_10"} 919
telemt_desync_frames_bucket_total{bucket="gt_10"} 800
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 15650
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 15437
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 191
telemt_user_connections_total{user="hello"} 560150
telemt_user_connections_current{user="hello"} 488
telemt_user_octets_from_client{user="hello"} 5845585150 (5.44 GB)
telemt_user_octets_to_client{user="hello"} 158601047660 (147.71 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 76891.6 (21h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1148801
telemt_connections_bad_total 7876
telemt_handshake_timeouts_total 108154
telemt_upstream_connect_attempt_total 20757
telemt_upstream_connect_success_total 20507
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 20757
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11177
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9230
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_keepalive_timeout_total 828
telemt_me_reconnect_attempts_total 29192
telemt_me_reconnect_success_total 15563
telemt_me_reader_eof_total 16709
telemt_me_idle_close_by_peer_total 16709
telemt_me_route_drop_no_conn_total 384553
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 988160
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2695
telemt_desync_full_logged_total 801
telemt_desync_suppressed_total 1894
telemt_desync_frames_bucket_total{bucket="1_2"} 632
telemt_desync_frames_bucket_total{bucket="3_10"} 1012
telemt_desync_frames_bucket_total{bucket="gt_10"} 1051
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 16191
telemt_me_refill_failed_total 422
telemt_me_writer_restored_same_endpoint_total 15552
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 628
telemt_user_connections_total{user="hello"} 988887
telemt_user_connections_current{user="hello"} 805
telemt_user_octets_from_client{user="hello"} 11485938733 (10.70 GB)
telemt_user_octets_to_client{user="hello"} 299567921581 (278.99 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 76892.0 (21h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 828846
telemt_connections_bad_total 72197
telemt_handshake_timeouts_total 75955
telemt_upstream_connect_attempt_total 20807
telemt_upstream_connect_success_total 20807
telemt_upstream_connect_attempts_per_request{bucket="1"} 20807
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11450
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9353
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 830
telemt_me_reconnect_attempts_total 18023
telemt_me_reconnect_success_total 16962
telemt_me_reader_eof_total 18012
telemt_me_idle_close_by_peer_total 18011
telemt_me_seq_mismatch_total 15
telemt_me_route_drop_no_conn_total 264101
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 657150
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1433
telemt_desync_full_logged_total 552
telemt_desync_suppressed_total 881
telemt_desync_frames_bucket_total{bucket="1_2"} 507
telemt_desync_frames_bucket_total{bucket="3_10"} 522
telemt_desync_frames_bucket_total{bucket="gt_10"} 404
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 17168
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 16936
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 206
telemt_user_connections_total{user="hello"} 656516
telemt_user_connections_current{user="hello"} 501
telemt_user_octets_from_client{user="hello"} 7513476976 (7.00 GB)
telemt_user_octets_to_client{user="hello"} 186022554016 (173.25 GB)
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 76891.9 (21h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 893347
telemt_connections_bad_total 6237
telemt_handshake_timeouts_total 8510
telemt_upstream_connect_attempt_total 21142
telemt_upstream_connect_success_total 21049
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 21142
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10783
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10091
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 171
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 891
telemt_me_reconnect_attempts_total 21144
telemt_me_reconnect_success_total 17085
telemt_me_reader_eof_total 18033
telemt_me_idle_close_by_peer_total 18033
telemt_me_route_drop_no_conn_total 313379
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 810793
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3331
telemt_desync_full_logged_total 1231
telemt_desync_suppressed_total 2100
telemt_desync_frames_bucket_total{bucket="1_2"} 1140
telemt_desync_frames_bucket_total{bucket="3_10"} 1306
telemt_desync_frames_bucket_total{bucket="gt_10"} 885
telemt_pool_swap_total 53
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 17429
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 17085
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 344
telemt_user_connections_total{user="hello"} 810550
telemt_user_connections_current{user="hello"} 721
telemt_user_octets_from_client{user="hello"} 12153757787 (11.32 GB)
telemt_user_octets_to_client{user="hello"} 294213344242 (274.01 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 115
```