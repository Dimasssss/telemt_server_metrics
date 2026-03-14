# Server Metrics 2026-03-14 11:16:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 191869.0 (53h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5531241
telemt_connections_bad_total 56459
telemt_handshake_timeouts_total 122075
telemt_upstream_connect_attempt_total 40280
telemt_upstream_connect_success_total 40023
telemt_upstream_connect_fail_total 257
telemt_upstream_connect_attempts_per_request{bucket="1"} 40280
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18174
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 157
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 257
telemt_me_keepalive_timeout_total 7680
telemt_me_reconnect_attempts_total 44494
telemt_me_reconnect_success_total 28122
telemt_me_reader_eof_total 30282
telemt_me_idle_close_by_peer_total 30281
telemt_me_route_drop_no_conn_total 2092961
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5072475
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19382
telemt_desync_full_logged_total 5307
telemt_desync_suppressed_total 14075
telemt_desync_frames_bucket_total{bucket="1_2"} 4723
telemt_desync_frames_bucket_total{bucket="3_10"} 7401
telemt_desync_frames_bucket_total{bucket="gt_10"} 7258
telemt_pool_swap_total 162
telemt_me_writer_removed_unexpected_total 29045
telemt_me_refill_failed_total 506
telemt_me_writer_restored_same_endpoint_total 28109
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 923
telemt_user_connections_total{user="hello"} 5073927
telemt_user_connections_current{user="hello"} 1827
telemt_user_octets_from_client{user="hello"} 78527216720 (73.13 GB)
telemt_user_octets_to_client{user="hello"} 1615646533861 (1.47 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 483
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 91532.9 (25h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1042105
telemt_connections_bad_total 58377
telemt_handshake_timeouts_total 23099
telemt_upstream_connect_attempt_total 24019
telemt_upstream_connect_success_total 23724
telemt_upstream_connect_fail_total 295
telemt_upstream_connect_attempts_per_request{bucket="1"} 24019
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12909
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10508
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 47
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 260
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 295
telemt_me_keepalive_timeout_total 2297
telemt_me_reconnect_attempts_total 29421
telemt_me_reconnect_success_total 17141
telemt_me_reader_eof_total 18414
telemt_me_idle_close_by_peer_total 18413
telemt_me_route_drop_no_conn_total 351099
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 854672
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2417
telemt_desync_full_logged_total 753
telemt_desync_suppressed_total 1664
telemt_desync_frames_bucket_total{bucket="1_2"} 603
telemt_desync_frames_bucket_total{bucket="3_10"} 1016
telemt_desync_frames_bucket_total{bucket="gt_10"} 798
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 17769
telemt_me_refill_failed_total 377
telemt_me_writer_restored_same_endpoint_total 17133
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 628
telemt_user_connections_total{user="hello"} 856586
telemt_user_connections_current{user="hello"} 670
telemt_user_octets_from_client{user="hello"} 9340487669 (8.70 GB)
telemt_user_octets_to_client{user="hello"} 299577045832 (279.00 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 221489.8 (61h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3924838
telemt_connections_bad_total 46150
telemt_handshake_timeouts_total 262133
telemt_upstream_connect_attempt_total 49937
telemt_upstream_connect_success_total 49916
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 49937
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23282
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 254
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 11071
telemt_me_reconnect_attempts_total 44561
telemt_me_reconnect_success_total 38563
telemt_me_reader_eof_total 40961
telemt_me_idle_close_by_peer_total 40959
telemt_me_route_drop_no_conn_total 1349617
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3282428
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10575
telemt_desync_full_logged_total 3576
telemt_desync_suppressed_total 6999
telemt_desync_frames_bucket_total{bucket="1_2"} 1917
telemt_desync_frames_bucket_total{bucket="3_10"} 3824
telemt_desync_frames_bucket_total{bucket="gt_10"} 4834
telemt_pool_swap_total 205
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 39134
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 38522
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 571
telemt_user_connections_total{user="hello"} 3281573
telemt_user_connections_current{user="hello"} 951
telemt_user_octets_from_client{user="hello"} 55726292660 (51.90 GB)
telemt_user_octets_to_client{user="hello"} 1173821682337 (1.07 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 289
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 221492.1 (61h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2576886
telemt_connections_bad_total 23470
telemt_handshake_timeouts_total 327365
telemt_upstream_connect_attempt_total 68604
telemt_upstream_connect_success_total 66099
telemt_upstream_connect_fail_total 2368
telemt_upstream_connect_attempts_per_request{bucket="1"} 68330
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39387
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26546
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2367
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20802
telemt_me_reconnect_attempts_total 60815
telemt_me_reconnect_success_total 48037
telemt_me_reader_eof_total 51462
telemt_me_idle_close_by_peer_total 51454
telemt_me_route_drop_no_conn_total 858673
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2017598
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4080
telemt_desync_full_logged_total 1338
telemt_desync_suppressed_total 2742
telemt_desync_frames_bucket_total{bucket="1_2"} 1156
telemt_desync_frames_bucket_total{bucket="3_10"} 1665
telemt_desync_frames_bucket_total{bucket="gt_10"} 1259
telemt_pool_swap_total 189
telemt_me_writer_removed_unexpected_total 48853
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 48012
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 816
telemt_user_connections_total{user="hello"} 2023910
telemt_user_connections_current{user="hello"} 497
telemt_user_octets_from_client{user="hello"} 30045006427 (27.98 GB)
telemt_user_octets_to_client{user="hello"} 726034645502 (676.17 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 90925.8 (25h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1028777
telemt_connections_bad_total 18065
telemt_handshake_timeouts_total 13497
telemt_upstream_connect_attempt_total 22458
telemt_upstream_connect_success_total 21848
telemt_upstream_connect_fail_total 610
telemt_upstream_connect_attempts_per_request{bucket="1"} 22458
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10474
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11348
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 610
telemt_me_keepalive_timeout_total 1732
telemt_me_reconnect_attempts_total 78271
telemt_me_reconnect_success_total 17330
telemt_me_reader_eof_total 19643
telemt_me_idle_close_by_peer_total 19642
telemt_me_route_drop_no_conn_total 401093
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 951250
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2558
telemt_desync_full_logged_total 800
telemt_desync_suppressed_total 1758
telemt_desync_frames_bucket_total{bucket="1_2"} 893
telemt_desync_frames_bucket_total{bucket="3_10"} 929
telemt_desync_frames_bucket_total{bucket="gt_10"} 736
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 19392
telemt_me_refill_failed_total 1899
telemt_me_writer_restored_same_endpoint_total 17325
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 2062
telemt_user_connections_total{user="hello"} 951187
telemt_user_connections_current{user="hello"} 612
telemt_user_octets_from_client{user="hello"} 16800974664 (15.65 GB)
telemt_user_octets_to_client{user="hello"} 320924758972 (298.88 GB)
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 86
```