# Server Metrics 2026-03-14 11:11:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 191561.9 (53h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5518592
telemt_connections_bad_total 56234
telemt_handshake_timeouts_total 121643
telemt_upstream_connect_attempt_total 40191
telemt_upstream_connect_success_total 39934
telemt_upstream_connect_fail_total 257
telemt_upstream_connect_attempts_per_request{bucket="1"} 40191
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21643
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18135
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 156
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 257
telemt_me_keepalive_timeout_total 7670
telemt_me_reconnect_attempts_total 44449
telemt_me_reconnect_success_total 28078
telemt_me_reader_eof_total 30233
telemt_me_idle_close_by_peer_total 30232
telemt_me_route_drop_no_conn_total 2088586
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5060737
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19326
telemt_desync_full_logged_total 5293
telemt_desync_suppressed_total 14033
telemt_desync_frames_bucket_total{bucket="1_2"} 4715
telemt_desync_frames_bucket_total{bucket="3_10"} 7374
telemt_desync_frames_bucket_total{bucket="gt_10"} 7237
telemt_pool_swap_total 161
telemt_me_writer_removed_unexpected_total 29000
telemt_me_refill_failed_total 506
telemt_me_writer_restored_same_endpoint_total 28065
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 922
telemt_user_connections_total{user="hello"} 5062189
telemt_user_connections_current{user="hello"} 1743
telemt_user_octets_from_client{user="hello"} 78065612536 (72.70 GB)
telemt_user_octets_to_client{user="hello"} 1611737932957 (1.47 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 473
telemt_user_unique_ips_recent_window{user="hello"} 239
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 91226.0 (25h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1037818
telemt_connections_bad_total 58374
telemt_handshake_timeouts_total 23027
telemt_upstream_connect_attempt_total 23978
telemt_upstream_connect_success_total 23683
telemt_upstream_connect_fail_total 295
telemt_upstream_connect_attempts_per_request{bucket="1"} 23978
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10495
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 47
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 259
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 295
telemt_me_keepalive_timeout_total 2297
telemt_me_reconnect_attempts_total 29380
telemt_me_reconnect_success_total 17100
telemt_me_reader_eof_total 18373
telemt_me_idle_close_by_peer_total 18372
telemt_me_route_drop_no_conn_total 349651
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 850587
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2409
telemt_desync_full_logged_total 749
telemt_desync_suppressed_total 1660
telemt_desync_frames_bucket_total{bucket="1_2"} 598
telemt_desync_frames_bucket_total{bucket="3_10"} 1013
telemt_desync_frames_bucket_total{bucket="gt_10"} 798
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 17728
telemt_me_refill_failed_total 377
telemt_me_writer_restored_same_endpoint_total 17092
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 628
telemt_user_connections_total{user="hello"} 852500
telemt_user_connections_current{user="hello"} 742
telemt_user_octets_from_client{user="hello"} 9271117833 (8.63 GB)
telemt_user_octets_to_client{user="hello"} 298206932492 (277.73 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 221182.5 (61h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3918043
telemt_connections_bad_total 46149
telemt_handshake_timeouts_total 261633
telemt_upstream_connect_attempt_total 49882
telemt_upstream_connect_success_total 49861
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 49882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26339
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23261
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 254
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 11071
telemt_me_reconnect_attempts_total 44534
telemt_me_reconnect_success_total 38536
telemt_me_reader_eof_total 40934
telemt_me_idle_close_by_peer_total 40932
telemt_me_route_drop_no_conn_total 1346635
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3276263
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10546
telemt_desync_full_logged_total 3569
telemt_desync_suppressed_total 6977
telemt_desync_frames_bucket_total{bucket="1_2"} 1905
telemt_desync_frames_bucket_total{bucket="3_10"} 3818
telemt_desync_frames_bucket_total{bucket="gt_10"} 4823
telemt_pool_swap_total 205
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 39107
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 38495
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 571
telemt_user_connections_total{user="hello"} 3275408
telemt_user_connections_current{user="hello"} 1141
telemt_user_octets_from_client{user="hello"} 55311489744 (51.51 GB)
telemt_user_octets_to_client{user="hello"} 1171378020425 (1.07 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 311
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 221185.3 (61h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2572919
telemt_connections_bad_total 23455
telemt_handshake_timeouts_total 326712
telemt_upstream_connect_attempt_total 68516
telemt_upstream_connect_success_total 66011
telemt_upstream_connect_fail_total 2368
telemt_upstream_connect_attempts_per_request{bucket="1"} 68242
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39337
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26508
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2367
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20801
telemt_me_reconnect_attempts_total 60756
telemt_me_reconnect_success_total 47978
telemt_me_reader_eof_total 51402
telemt_me_idle_close_by_peer_total 51394
telemt_me_route_drop_no_conn_total 857492
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2014641
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4066
telemt_desync_full_logged_total 1333
telemt_desync_suppressed_total 2733
telemt_desync_frames_bucket_total{bucket="1_2"} 1152
telemt_desync_frames_bucket_total{bucket="3_10"} 1659
telemt_desync_frames_bucket_total{bucket="gt_10"} 1255
telemt_pool_swap_total 189
telemt_me_writer_removed_unexpected_total 48793
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 47953
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 815
telemt_user_connections_total{user="hello"} 2020942
telemt_user_connections_current{user="hello"} 402
telemt_user_octets_from_client{user="hello"} 30010192827 (27.95 GB)
telemt_user_octets_to_client{user="hello"} 724711995634 (674.94 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 90618.4 (25h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1024659
telemt_connections_bad_total 18063
telemt_handshake_timeouts_total 13465
telemt_upstream_connect_attempt_total 22436
telemt_upstream_connect_success_total 21826
telemt_upstream_connect_fail_total 610
telemt_upstream_connect_attempts_per_request{bucket="1"} 22436
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10461
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11339
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 610
telemt_me_keepalive_timeout_total 1732
telemt_me_reconnect_attempts_total 78249
telemt_me_reconnect_success_total 17308
telemt_me_reader_eof_total 19621
telemt_me_idle_close_by_peer_total 19620
telemt_me_route_drop_no_conn_total 398935
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 947569
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2552
telemt_desync_full_logged_total 797
telemt_desync_suppressed_total 1755
telemt_desync_frames_bucket_total{bucket="1_2"} 887
telemt_desync_frames_bucket_total{bucket="3_10"} 929
telemt_desync_frames_bucket_total{bucket="gt_10"} 736
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 19370
telemt_me_refill_failed_total 1899
telemt_me_writer_restored_same_endpoint_total 17303
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 2062
telemt_user_connections_total{user="hello"} 947506
telemt_user_connections_current{user="hello"} 637
telemt_user_octets_from_client{user="hello"} 16760206412 (15.61 GB)
telemt_user_octets_to_client{user="hello"} 318597737388 (296.72 GB)
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 91
```