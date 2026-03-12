# Server Metrics 2026-03-12 15:51:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 35565.2 (9h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1280657
telemt_connections_bad_total 20236
telemt_handshake_timeouts_total 12629
telemt_upstream_connect_attempt_total 7110
telemt_upstream_connect_success_total 7071
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 7110
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3767
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3288
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 419
telemt_me_reconnect_attempts_total 9165
telemt_me_reconnect_success_total 5258
telemt_me_reader_eof_total 5606
telemt_me_idle_close_by_peer_total 5605
telemt_me_route_drop_no_conn_total 458369
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1203718
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6291
telemt_desync_full_logged_total 1571
telemt_desync_suppressed_total 4720
telemt_desync_frames_bucket_total{bucket="1_2"} 1619
telemt_desync_frames_bucket_total{bucket="3_10"} 2261
telemt_desync_frames_bucket_total{bucket="gt_10"} 2411
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5446
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 5245
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 1203400
telemt_user_connections_current{user="hello"} 1625
telemt_user_octets_from_client{user="hello"} 18767157432 (17.48 GB)
telemt_user_octets_to_client{user="hello"} 348829994976 (324.87 GB)
telemt_user_unique_ips_current{user="hello"} 436
telemt_user_unique_ips_recent_window{user="hello"} 198
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 65185.7 (18h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 573517
telemt_connections_bad_total 7371
telemt_handshake_timeouts_total 27536
telemt_upstream_connect_attempt_total 15646
telemt_upstream_connect_success_total 15639
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 15646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7783
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7840
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1204
telemt_me_reconnect_attempts_total 12263
telemt_me_reconnect_success_total 12193
telemt_me_reader_eof_total 12962
telemt_me_idle_close_by_peer_total 12962
telemt_me_route_drop_no_conn_total 169628
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 512525
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2007
telemt_desync_full_logged_total 628
telemt_desync_suppressed_total 1379
telemt_desync_frames_bucket_total{bucket="1_2"} 885
telemt_desync_frames_bucket_total{bucket="3_10"} 636
telemt_desync_frames_bucket_total{bucket="gt_10"} 486
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 12314
telemt_me_writer_restored_same_endpoint_total 12184
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 513020
telemt_user_connections_current{user="hello"} 524
telemt_user_octets_from_client{user="hello"} 7948386223 (7.40 GB)
telemt_user_octets_to_client{user="hello"} 182472065886 (169.94 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 65185.7 (18h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1214856
telemt_connections_bad_total 6255
telemt_handshake_timeouts_total 84494
telemt_upstream_connect_attempt_total 15707
telemt_upstream_connect_success_total 15702
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 15707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8492
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7145
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1011
telemt_me_reconnect_attempts_total 13303
telemt_me_reconnect_success_total 12077
telemt_me_reader_eof_total 12731
telemt_me_idle_close_by_peer_total 12731
telemt_me_route_drop_no_conn_total 329335
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 898654
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3777
telemt_desync_full_logged_total 1160
telemt_desync_suppressed_total 2617
telemt_desync_frames_bucket_total{bucket="1_2"} 575
telemt_desync_frames_bucket_total{bucket="3_10"} 1367
telemt_desync_frames_bucket_total{bucket="gt_10"} 1835
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 12164
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 12036
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 898836
telemt_user_connections_current{user="hello"} 921
telemt_user_octets_from_client{user="hello"} 11903304828 (11.09 GB)
telemt_user_octets_to_client{user="hello"} 281166455929 (261.86 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 65186.3 (18h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 721738
telemt_connections_bad_total 7713
telemt_handshake_timeouts_total 58267
telemt_upstream_connect_attempt_total 17153
telemt_upstream_connect_success_total 17084
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 17153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9691
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7380
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 1393
telemt_me_reconnect_attempts_total 19059
telemt_me_reconnect_success_total 13817
telemt_me_reader_eof_total 14737
telemt_me_idle_close_by_peer_total 14737
telemt_me_route_drop_no_conn_total 245816
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 621277
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1252
telemt_desync_full_logged_total 425
telemt_desync_suppressed_total 827
telemt_desync_frames_bucket_total{bucket="1_2"} 333
telemt_desync_frames_bucket_total{bucket="3_10"} 497
telemt_desync_frames_bucket_total{bucket="gt_10"} 422
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 14085
telemt_me_refill_failed_total 162
telemt_me_writer_restored_same_endpoint_total 13796
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 268
telemt_user_connections_total{user="hello"} 620764
telemt_user_connections_current{user="hello"} 500
telemt_user_octets_from_client{user="hello"} 7850541656 (7.31 GB)
telemt_user_octets_to_client{user="hello"} 245525304652 (228.66 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 65186.1 (18h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 816563
telemt_connections_bad_total 8777
telemt_handshake_timeouts_total 6507
telemt_upstream_connect_attempt_total 20601
telemt_upstream_connect_success_total 20348
telemt_upstream_connect_fail_total 253
telemt_upstream_connect_attempts_per_request{bucket="1"} 20601
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10337
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9902
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 253
telemt_me_keepalive_timeout_total 1145
telemt_me_reconnect_attempts_total 24317
telemt_me_reconnect_success_total 17079
telemt_me_reader_eof_total 17893
telemt_me_idle_close_by_peer_total 17893
telemt_me_seq_mismatch_total 28
telemt_me_route_drop_no_conn_total 285738
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 752600
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 32
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2949
telemt_desync_full_logged_total 999
telemt_desync_suppressed_total 1950
telemt_desync_frames_bucket_total{bucket="1_2"} 834
telemt_desync_frames_bucket_total{bucket="3_10"} 1009
telemt_desync_frames_bucket_total{bucket="gt_10"} 1106
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 17482
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 17042
telemt_me_writer_restored_fallback_total 37
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 403
telemt_user_connections_total{user="hello"} 752497
telemt_user_connections_current{user="hello"} 797
telemt_user_octets_from_client{user="hello"} 9099151764 (8.47 GB)
telemt_user_octets_to_client{user="hello"} 210908568400 (196.42 GB)
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 106
```