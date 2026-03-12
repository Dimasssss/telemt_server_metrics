# Server Metrics 2026-03-12 16:11:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 36791.1 (10h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1329811
telemt_connections_bad_total 20239
telemt_handshake_timeouts_total 12851
telemt_upstream_connect_attempt_total 7317
telemt_upstream_connect_success_total 7278
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 7317
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3400
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 456
telemt_me_reconnect_attempts_total 9327
telemt_me_reconnect_success_total 5417
telemt_me_reader_eof_total 5767
telemt_me_idle_close_by_peer_total 5766
telemt_me_route_drop_no_conn_total 476294
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1246212
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6457
telemt_desync_full_logged_total 1618
telemt_desync_suppressed_total 4839
telemt_desync_frames_bucket_total{bucket="1_2"} 1664
telemt_desync_frames_bucket_total{bucket="3_10"} 2327
telemt_desync_frames_bucket_total{bucket="gt_10"} 2466
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5607
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 5404
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 1245891
telemt_user_connections_current{user="hello"} 1637
telemt_user_octets_from_client{user="hello"} 19224118692 (17.90 GB)
telemt_user_octets_to_client{user="hello"} 360255200776 (335.51 GB)
telemt_user_unique_ips_current{user="hello"} 442
telemt_user_unique_ips_recent_window{user="hello"} 238
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 66411.5 (18h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 589368
telemt_connections_bad_total 7757
telemt_handshake_timeouts_total 27736
telemt_upstream_connect_attempt_total 15870
telemt_upstream_connect_success_total 15863
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 15870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7886
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7961
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1256
telemt_me_reconnect_attempts_total 12443
telemt_me_reconnect_success_total 12372
telemt_me_reader_eof_total 13152
telemt_me_idle_close_by_peer_total 13152
telemt_me_route_drop_no_conn_total 175769
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 527427
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2052
telemt_desync_full_logged_total 649
telemt_desync_suppressed_total 1403
telemt_desync_frames_bucket_total{bucket="1_2"} 911
telemt_desync_frames_bucket_total{bucket="3_10"} 649
telemt_desync_frames_bucket_total{bucket="gt_10"} 492
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 12495
telemt_me_writer_restored_same_endpoint_total 12363
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 527915
telemt_user_connections_current{user="hello"} 605
telemt_user_octets_from_client{user="hello"} 8152166971 (7.59 GB)
telemt_user_octets_to_client{user="hello"} 186393342062 (173.59 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 66411.5 (18h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1244702
telemt_connections_bad_total 6272
telemt_handshake_timeouts_total 87909
telemt_upstream_connect_attempt_total 15957
telemt_upstream_connect_success_total 15952
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 15957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8626
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7261
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1062
telemt_me_reconnect_attempts_total 13509
telemt_me_reconnect_success_total 12280
telemt_me_reader_eof_total 12949
telemt_me_idle_close_by_peer_total 12949
telemt_me_route_drop_no_conn_total 340667
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 924564
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3940
telemt_desync_full_logged_total 1203
telemt_desync_suppressed_total 2737
telemt_desync_frames_bucket_total{bucket="1_2"} 606
telemt_desync_frames_bucket_total{bucket="3_10"} 1417
telemt_desync_frames_bucket_total{bucket="gt_10"} 1917
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 12370
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 12239
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 924737
telemt_user_connections_current{user="hello"} 899
telemt_user_octets_from_client{user="hello"} 12110915036 (11.28 GB)
telemt_user_octets_to_client{user="hello"} 289292468773 (269.42 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 268
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 66411.9 (18h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 742484
telemt_connections_bad_total 7725
telemt_handshake_timeouts_total 59517
telemt_upstream_connect_attempt_total 17471
telemt_upstream_connect_success_total 17402
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 17471
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7534
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 1477
telemt_me_reconnect_attempts_total 19332
telemt_me_reconnect_success_total 14088
telemt_me_reader_eof_total 15009
telemt_me_idle_close_by_peer_total 15009
telemt_me_route_drop_no_conn_total 253764
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 640183
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1256
telemt_desync_full_logged_total 426
telemt_desync_suppressed_total 830
telemt_desync_frames_bucket_total{bucket="1_2"} 335
telemt_desync_frames_bucket_total{bucket="3_10"} 498
telemt_desync_frames_bucket_total{bucket="gt_10"} 423
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 14358
telemt_me_refill_failed_total 162
telemt_me_writer_restored_same_endpoint_total 14067
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 270
telemt_user_connections_total{user="hello"} 639650
telemt_user_connections_current{user="hello"} 615
telemt_user_octets_from_client{user="hello"} 8025475204 (7.47 GB)
telemt_user_octets_to_client{user="hello"} 251047521804 (233.81 GB)
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## server5

Не удалось получить метрики для этого сервера.