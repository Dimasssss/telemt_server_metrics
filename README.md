# Server Metrics 2026-03-13 11:08:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 104969.3 (29h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3070552
telemt_connections_bad_total 36459
telemt_handshake_timeouts_total 54727
telemt_upstream_connect_attempt_total 20715
telemt_upstream_connect_success_total 20604
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 20715
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9971
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_timeout_total 1465
telemt_me_reconnect_attempts_total 25455
telemt_me_reconnect_success_total 15382
telemt_me_reader_eof_total 16547
telemt_me_idle_close_by_peer_total 16546
telemt_me_route_drop_no_conn_total 1135228
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2805073
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12167
telemt_desync_full_logged_total 3140
telemt_desync_suppressed_total 9027
telemt_desync_frames_bucket_total{bucket="1_2"} 3114
telemt_desync_frames_bucket_total{bucket="3_10"} 4556
telemt_desync_frames_bucket_total{bucket="gt_10"} 4497
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 15908
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 15369
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 526
telemt_user_connections_total{user="hello"} 2805013
telemt_user_connections_current{user="hello"} 1892
telemt_user_octets_from_client{user="hello"} 38756488908 (36.09 GB)
telemt_user_octets_to_client{user="hello"} 910866543268 (848.31 GB)
telemt_user_unique_ips_current{user="hello"} 460
telemt_user_unique_ips_recent_window{user="hello"} 264
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 4633.0 (1h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55512
telemt_connections_bad_total 4734
telemt_handshake_timeouts_total 1339
telemt_upstream_connect_attempt_total 1372
telemt_upstream_connect_success_total 1303
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 1372
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 649
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 643
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 1327
telemt_me_reconnect_success_total 1001
telemt_me_reader_eof_total 1002
telemt_me_idle_close_by_peer_total 1002
telemt_me_route_drop_no_conn_total 19600
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48099
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 127
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 90
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 39
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1009
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 994
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 48097
telemt_user_connections_current{user="hello"} 519
telemt_user_octets_from_client{user="hello"} 522262596 (498.07 MB)
telemt_user_octets_to_client{user="hello"} 12236983220 (11.40 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 134589.8 (37h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2364039
telemt_connections_bad_total 25180
telemt_handshake_timeouts_total 158708
telemt_upstream_connect_attempt_total 30634
telemt_upstream_connect_success_total 30624
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 30634
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16044
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14459
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 116
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1929
telemt_me_reconnect_attempts_total 24869
telemt_me_reconnect_success_total 23575
telemt_me_reader_eof_total 24979
telemt_me_idle_close_by_peer_total 24978
telemt_me_route_drop_no_conn_total 779275
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1906094
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6302
telemt_desync_full_logged_total 2020
telemt_desync_suppressed_total 4282
telemt_desync_frames_bucket_total{bucket="1_2"} 1009
telemt_desync_frames_bucket_total{bucket="3_10"} 2304
telemt_desync_frames_bucket_total{bucket="gt_10"} 2989
telemt_pool_swap_total 127
telemt_me_writer_removed_unexpected_total 23811
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 23534
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 236
telemt_user_connections_total{user="hello"} 1905518
telemt_user_connections_current{user="hello"} 1176
telemt_user_octets_from_client{user="hello"} 32570115032 (30.33 GB)
telemt_user_octets_to_client{user="hello"} 684168397753 (637.18 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 315
telemt_user_unique_ips_recent_window{user="hello"} 183
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 134590.1 (37h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1495553
telemt_connections_bad_total 15412
telemt_handshake_timeouts_total 96113
telemt_upstream_connect_attempt_total 43832
telemt_upstream_connect_success_total 41519
telemt_upstream_connect_fail_total 2176
telemt_upstream_connect_attempts_per_request{bucket="1"} 43558
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2175
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11555
telemt_me_reconnect_attempts_total 37915
telemt_me_reconnect_success_total 28960
telemt_me_reader_eof_total 31150
telemt_me_idle_close_by_peer_total 31143
telemt_me_route_drop_no_conn_total 531331
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1250301
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2328
telemt_desync_full_logged_total 777
telemt_desync_suppressed_total 1551
telemt_desync_frames_bucket_total{bucket="1_2"} 650
telemt_desync_frames_bucket_total{bucket="3_10"} 883
telemt_desync_frames_bucket_total{bucket="gt_10"} 795
telemt_pool_swap_total 116
telemt_me_writer_removed_unexpected_total 29452
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 28936
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 492
telemt_user_connections_total{user="hello"} 1255026
telemt_user_connections_current{user="hello"} 628
telemt_user_octets_from_client{user="hello"} 18948687189 (17.65 GB)
telemt_user_octets_to_client{user="hello"} 494160363574 (460.22 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 4026.5 (1h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53653
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 280
telemt_upstream_connect_attempt_total 1023
telemt_upstream_connect_success_total 997
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 1023
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 416
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 581
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 3340
telemt_me_reconnect_success_total 745
telemt_me_reader_eof_total 796
telemt_me_idle_close_by_peer_total 796
telemt_me_route_drop_no_conn_total 19160
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51441
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 220
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 149
telemt_desync_frames_bucket_total{bucket="1_2"} 104
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_me_writer_removed_unexpected_total 817
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 741
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 51431
telemt_user_connections_current{user="hello"} 797
telemt_user_octets_from_client{user="hello"} 513618996 (489.83 MB)
telemt_user_octets_to_client{user="hello"} 19195061844 (17.88 GB)
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 101
```