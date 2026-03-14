# Server Metrics 2026-03-14 11:21:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 192175.9 (53h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5543551
telemt_connections_bad_total 56676
telemt_handshake_timeouts_total 122395
telemt_upstream_connect_attempt_total 40328
telemt_upstream_connect_success_total 40071
telemt_upstream_connect_fail_total 257
telemt_upstream_connect_attempts_per_request{bucket="1"} 40328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21716
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18198
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 157
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 257
telemt_me_keepalive_timeout_total 7696
telemt_me_reconnect_attempts_total 44542
telemt_me_reconnect_success_total 28171
telemt_me_reader_eof_total 30333
telemt_me_idle_close_by_peer_total 30332
telemt_me_route_drop_no_conn_total 2097431
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5084059
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19407
telemt_desync_full_logged_total 5314
telemt_desync_suppressed_total 14093
telemt_desync_frames_bucket_total{bucket="1_2"} 4728
telemt_desync_frames_bucket_total{bucket="3_10"} 7407
telemt_desync_frames_bucket_total{bucket="gt_10"} 7272
telemt_pool_swap_total 162
telemt_me_writer_removed_unexpected_total 29093
telemt_me_refill_failed_total 506
telemt_me_writer_restored_same_endpoint_total 28158
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 922
telemt_user_connections_total{user="hello"} 5085503
telemt_user_connections_current{user="hello"} 1700
telemt_user_octets_from_client{user="hello"} 78646271580 (73.25 GB)
telemt_user_octets_to_client{user="hello"} 1619147387077 (1.47 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 458
telemt_user_unique_ips_recent_window{user="hello"} 198
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 91839.7 (25h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1046898
telemt_connections_bad_total 58568
telemt_handshake_timeouts_total 23336
telemt_upstream_connect_attempt_total 24073
telemt_upstream_connect_success_total 23778
telemt_upstream_connect_fail_total 295
telemt_upstream_connect_attempts_per_request{bucket="1"} 24073
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12943
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10527
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 260
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 295
telemt_me_keepalive_timeout_total 2297
telemt_me_reconnect_attempts_total 29464
telemt_me_reconnect_success_total 17184
telemt_me_reader_eof_total 18457
telemt_me_idle_close_by_peer_total 18456
telemt_me_route_drop_no_conn_total 352765
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 858749
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2421
telemt_desync_full_logged_total 756
telemt_desync_suppressed_total 1665
telemt_desync_frames_bucket_total{bucket="1_2"} 604
telemt_desync_frames_bucket_total{bucket="3_10"} 1017
telemt_desync_frames_bucket_total{bucket="gt_10"} 800
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 17812
telemt_me_refill_failed_total 377
telemt_me_writer_restored_same_endpoint_total 17176
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 628
telemt_user_connections_total{user="hello"} 860667
telemt_user_connections_current{user="hello"} 726
telemt_user_octets_from_client{user="hello"} 9388541961 (8.74 GB)
telemt_user_octets_to_client{user="hello"} 300385721840 (279.76 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 221796.5 (61h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3932190
telemt_connections_bad_total 46152
telemt_handshake_timeouts_total 263070
telemt_upstream_connect_attempt_total 50066
telemt_upstream_connect_success_total 50045
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 50066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26443
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23340
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 255
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 11085
telemt_me_reconnect_attempts_total 44670
telemt_me_reconnect_success_total 38671
telemt_me_reader_eof_total 41071
telemt_me_idle_close_by_peer_total 41069
telemt_me_route_drop_no_conn_total 1352023
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3288663
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10607
telemt_desync_full_logged_total 3585
telemt_desync_suppressed_total 7022
telemt_desync_frames_bucket_total{bucket="1_2"} 1923
telemt_desync_frames_bucket_total{bucket="3_10"} 3840
telemt_desync_frames_bucket_total{bucket="gt_10"} 4844
telemt_pool_swap_total 205
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 39244
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 38630
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 573
telemt_user_connections_total{user="hello"} 3287808
telemt_user_connections_current{user="hello"} 1019
telemt_user_octets_from_client{user="hello"} 56059669792 (52.21 GB)
telemt_user_octets_to_client{user="hello"} 1177477201457 (1.07 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 296
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 221799.1 (61h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2580420
telemt_connections_bad_total 23470
telemt_handshake_timeouts_total 328141
telemt_upstream_connect_attempt_total 68695
telemt_upstream_connect_success_total 66189
telemt_upstream_connect_fail_total 2369
telemt_upstream_connect_attempts_per_request{bucket="1"} 68421
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39434
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26589
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2368
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20805
telemt_me_reconnect_attempts_total 60890
telemt_me_reconnect_success_total 48112
telemt_me_reader_eof_total 51554
telemt_me_idle_close_by_peer_total 51546
telemt_me_route_drop_no_conn_total 859865
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2020180
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4085
telemt_desync_full_logged_total 1341
telemt_desync_suppressed_total 2744
telemt_desync_frames_bucket_total{bucket="1_2"} 1160
telemt_desync_frames_bucket_total{bucket="3_10"} 1666
telemt_desync_frames_bucket_total{bucket="gt_10"} 1259
telemt_pool_swap_total 190
telemt_me_writer_removed_unexpected_total 48928
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 48087
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 816
telemt_user_connections_total{user="hello"} 2026507
telemt_user_connections_current{user="hello"} 451
telemt_user_octets_from_client{user="hello"} 30086314251 (28.02 GB)
telemt_user_octets_to_client{user="hello"} 726531605618 (676.64 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 91232.5 (25h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1032895
telemt_connections_bad_total 18067
telemt_handshake_timeouts_total 13545
telemt_upstream_connect_attempt_total 22529
telemt_upstream_connect_success_total 21919
telemt_upstream_connect_fail_total 610
telemt_upstream_connect_attempts_per_request{bucket="1"} 22529
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10512
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11381
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 610
telemt_me_keepalive_timeout_total 1741
telemt_me_reconnect_attempts_total 79674
telemt_me_reconnect_success_total 17357
telemt_me_reader_eof_total 19713
telemt_me_idle_close_by_peer_total 19712
telemt_me_route_drop_no_conn_total 418252
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 955652
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2575
telemt_desync_full_logged_total 803
telemt_desync_suppressed_total 1772
telemt_desync_frames_bucket_total{bucket="1_2"} 898
telemt_desync_frames_bucket_total{bucket="3_10"} 933
telemt_desync_frames_bucket_total{bucket="gt_10"} 744
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 19462
telemt_me_refill_failed_total 1942
telemt_me_writer_restored_same_endpoint_total 17352
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 2105
telemt_user_connections_total{user="hello"} 954866
telemt_user_connections_current{user="hello"} 639
telemt_user_octets_from_client{user="hello"} 16843296288 (15.69 GB)
telemt_user_octets_to_client{user="hello"} 322470635436 (300.32 GB)
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 83
```