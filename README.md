# Server Metrics 2026-03-14 00:11:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 151968.7 (42h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4593278
telemt_connections_bad_total 38395
telemt_handshake_timeouts_total 107814
telemt_upstream_connect_attempt_total 31943
telemt_upstream_connect_success_total 31726
telemt_upstream_connect_fail_total 217
telemt_upstream_connect_attempts_per_request{bucket="1"} 31943
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17396
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14185
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 217
telemt_me_keepalive_timeout_total 6657
telemt_me_reconnect_attempts_total 31957
telemt_me_reconnect_success_total 21825
telemt_me_reader_eof_total 23409
telemt_me_idle_close_by_peer_total 23408
telemt_me_route_drop_no_conn_total 1737907
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4210142
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16620
telemt_desync_full_logged_total 4478
telemt_desync_suppressed_total 12142
telemt_desync_frames_bucket_total{bucket="1_2"} 4135
telemt_desync_frames_bucket_total{bucket="3_10"} 6360
telemt_desync_frames_bucket_total{bucket="gt_10"} 6125
telemt_pool_swap_total 129
telemt_me_writer_removed_unexpected_total 22457
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 21812
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 632
telemt_user_connections_total{user="hello"} 4212022
telemt_user_connections_current{user="hello"} 567
telemt_user_octets_from_client{user="hello"} 62171049248 (57.90 GB)
telemt_user_octets_to_client{user="hello"} 1332157382141 (1.21 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 51632.5 (14h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 634634
telemt_connections_bad_total 47213
telemt_handshake_timeouts_total 12787
telemt_upstream_connect_attempt_total 14576
telemt_upstream_connect_success_total 14336
telemt_upstream_connect_fail_total 240
telemt_upstream_connect_attempts_per_request{bucket="1"} 14576
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5961
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 240
telemt_me_keepalive_timeout_total 1937
telemt_me_reconnect_attempts_total 13147
telemt_me_reconnect_success_total 9707
telemt_me_reader_eof_total 10300
telemt_me_idle_close_by_peer_total 10299
telemt_me_route_drop_no_conn_total 224179
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 532487
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1643
telemt_desync_full_logged_total 444
telemt_desync_suppressed_total 1199
telemt_desync_frames_bucket_total{bucket="1_2"} 348
telemt_desync_frames_bucket_total{bucket="3_10"} 712
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 9953
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 9699
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 246
telemt_user_connections_total{user="hello"} 534438
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 5834194269 (5.43 GB)
telemt_user_octets_to_client{user="hello"} 174080921888 (162.13 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 181589.3 (50h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3328700
telemt_connections_bad_total 32558
telemt_handshake_timeouts_total 222212
telemt_upstream_connect_attempt_total 40536
telemt_upstream_connect_success_total 40515
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 40536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19075
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10348
telemt_me_reconnect_attempts_total 36120
telemt_me_reconnect_success_total 31164
telemt_me_reader_eof_total 33079
telemt_me_idle_close_by_peer_total 33078
telemt_me_route_drop_no_conn_total 1142378
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2766695
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9065
telemt_desync_full_logged_total 3049
telemt_desync_suppressed_total 6016
telemt_desync_frames_bucket_total{bucket="1_2"} 1528
telemt_desync_frames_bucket_total{bucket="3_10"} 3286
telemt_desync_frames_bucket_total{bucket="gt_10"} 4251
telemt_pool_swap_total 169
telemt_me_writer_removed_unexpected_total 31616
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 31123
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 452
telemt_user_connections_total{user="hello"} 2765938
telemt_user_connections_current{user="hello"} 307
telemt_user_octets_from_client{user="hello"} 44811138776 (41.73 GB)
telemt_user_octets_to_client{user="hello"} 980902887889 (913.54 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 181591.8 (50h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2200890
telemt_connections_bad_total 22862
telemt_handshake_timeouts_total 234974
telemt_upstream_connect_attempt_total 56502
telemt_upstream_connect_success_total 54047
telemt_upstream_connect_fail_total 2318
telemt_upstream_connect_attempts_per_request{bucket="1"} 56228
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21496
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2317
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20372
telemt_me_reconnect_attempts_total 47015
telemt_me_reconnect_success_total 37990
telemt_me_reader_eof_total 40750
telemt_me_idle_close_by_peer_total 40743
telemt_me_route_drop_no_conn_total 763590
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1776242
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3798
telemt_desync_full_logged_total 1218
telemt_desync_suppressed_total 2580
telemt_desync_frames_bucket_total{bucket="1_2"} 1004
telemt_desync_frames_bucket_total{bucket="3_10"} 1588
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 159
telemt_me_writer_removed_unexpected_total 38600
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 37966
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 610
telemt_user_connections_total{user="hello"} 1782138
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 27374429623 (25.49 GB)
telemt_user_octets_to_client{user="hello"} 662267089710 (616.78 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 51025.2 (14h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 668550
telemt_connections_bad_total 7867
telemt_handshake_timeouts_total 8447
telemt_upstream_connect_attempt_total 12297
telemt_upstream_connect_success_total 11936
telemt_upstream_connect_fail_total 361
telemt_upstream_connect_attempts_per_request{bucket="1"} 12297
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5801
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6110
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 361
telemt_me_keepalive_timeout_total 1456
telemt_me_reconnect_attempts_total 41532
telemt_me_reconnect_success_total 9376
telemt_me_reader_eof_total 10563
telemt_me_idle_close_by_peer_total 10562
telemt_me_route_drop_no_conn_total 252254
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 621779
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1638
telemt_desync_full_logged_total 513
telemt_desync_suppressed_total 1125
telemt_desync_frames_bucket_total{bucket="1_2"} 492
telemt_desync_frames_bucket_total{bucket="3_10"} 641
telemt_desync_frames_bucket_total{bucket="gt_10"} 505
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 10466
telemt_me_refill_failed_total 1001
telemt_me_writer_restored_same_endpoint_total 9371
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1090
telemt_user_connections_total{user="hello"} 621678
telemt_user_connections_current{user="hello"} 219
telemt_user_octets_from_client{user="hello"} 10172801672 (9.47 GB)
telemt_user_octets_to_client{user="hello"} 202358464532 (188.46 GB)
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 21
```