# Server Metrics 2026-03-14 11:06:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 191255.2 (53h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5507023
telemt_connections_bad_total 56130
telemt_handshake_timeouts_total 121283
telemt_upstream_connect_attempt_total 40160
telemt_upstream_connect_success_total 39903
telemt_upstream_connect_fail_total 257
telemt_upstream_connect_attempts_per_request{bucket="1"} 40160
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21627
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18120
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 156
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 257
telemt_me_keepalive_timeout_total 7661
telemt_me_reconnect_attempts_total 44418
telemt_me_reconnect_success_total 28047
telemt_me_reader_eof_total 30201
telemt_me_idle_close_by_peer_total 30200
telemt_me_route_drop_no_conn_total 2083642
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5049898
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19286
telemt_desync_full_logged_total 5284
telemt_desync_suppressed_total 14002
telemt_desync_frames_bucket_total{bucket="1_2"} 4707
telemt_desync_frames_bucket_total{bucket="3_10"} 7356
telemt_desync_frames_bucket_total{bucket="gt_10"} 7223
telemt_pool_swap_total 161
telemt_me_writer_removed_unexpected_total 28967
telemt_me_refill_failed_total 506
telemt_me_writer_restored_same_endpoint_total 28034
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 920
telemt_user_connections_total{user="hello"} 5051358
telemt_user_connections_current{user="hello"} 1764
telemt_user_octets_from_client{user="hello"} 77714460864 (72.38 GB)
telemt_user_octets_to_client{user="hello"} 1608314951917 (1.46 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 479
telemt_user_unique_ips_recent_window{user="hello"} 232
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 90919.2 (25h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1033041
telemt_connections_bad_total 58372
telemt_handshake_timeouts_total 22955
telemt_upstream_connect_attempt_total 23889
telemt_upstream_connect_success_total 23595
telemt_upstream_connect_fail_total 294
telemt_upstream_connect_attempts_per_request{bucket="1"} 23889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12825
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10465
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 47
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 258
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 294
telemt_me_keepalive_timeout_total 2296
telemt_me_reconnect_attempts_total 28055
telemt_me_reconnect_success_total 17055
telemt_me_reader_eof_total 18288
telemt_me_idle_close_by_peer_total 18287
telemt_me_route_drop_no_conn_total 348194
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 846088
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2398
telemt_desync_full_logged_total 747
telemt_desync_suppressed_total 1651
telemt_desync_frames_bucket_total{bucket="1_2"} 588
telemt_desync_frames_bucket_total{bucket="3_10"} 1012
telemt_desync_frames_bucket_total{bucket="gt_10"} 798
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 17643
telemt_me_refill_failed_total 337
telemt_me_writer_restored_same_endpoint_total 17047
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 588
telemt_user_connections_total{user="hello"} 847993
telemt_user_connections_current{user="hello"} 699
telemt_user_octets_from_client{user="hello"} 9215173245 (8.58 GB)
telemt_user_octets_to_client{user="hello"} 296650374520 (276.28 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 220875.8 (61h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3910499
telemt_connections_bad_total 46022
telemt_handshake_timeouts_total 260953
telemt_upstream_connect_attempt_total 49855
telemt_upstream_connect_success_total 49834
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 49855
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23248
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 253
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 11063
telemt_me_reconnect_attempts_total 44507
telemt_me_reconnect_success_total 38509
telemt_me_reader_eof_total 40907
telemt_me_idle_close_by_peer_total 40905
telemt_me_route_drop_no_conn_total 1343722
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3269668
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10508
telemt_desync_full_logged_total 3561
telemt_desync_suppressed_total 6947
telemt_desync_frames_bucket_total{bucket="1_2"} 1900
telemt_desync_frames_bucket_total{bucket="3_10"} 3810
telemt_desync_frames_bucket_total{bucket="gt_10"} 4798
telemt_pool_swap_total 205
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 39080
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 38468
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 571
telemt_user_connections_total{user="hello"} 3268830
telemt_user_connections_current{user="hello"} 1098
telemt_user_octets_from_client{user="hello"} 55144473716 (51.36 GB)
telemt_user_octets_to_client{user="hello"} 1169120172813 (1.06 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 306
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 220878.4 (61h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2569409
telemt_connections_bad_total 23450
telemt_handshake_timeouts_total 326212
telemt_upstream_connect_attempt_total 68437
telemt_upstream_connect_success_total 65932
telemt_upstream_connect_fail_total 2368
telemt_upstream_connect_attempts_per_request{bucket="1"} 68163
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39292
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26474
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2367
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20794
telemt_me_reconnect_attempts_total 60677
telemt_me_reconnect_success_total 47900
telemt_me_reader_eof_total 51325
telemt_me_idle_close_by_peer_total 51317
telemt_me_route_drop_no_conn_total 855963
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2011802
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4062
telemt_desync_full_logged_total 1332
telemt_desync_suppressed_total 2730
telemt_desync_frames_bucket_total{bucket="1_2"} 1149
telemt_desync_frames_bucket_total{bucket="3_10"} 1659
telemt_desync_frames_bucket_total{bucket="gt_10"} 1254
telemt_pool_swap_total 189
telemt_me_writer_removed_unexpected_total 48715
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 47875
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 815
telemt_user_connections_total{user="hello"} 2018094
telemt_user_connections_current{user="hello"} 467
telemt_user_octets_from_client{user="hello"} 29993541687 (27.93 GB)
telemt_user_octets_to_client{user="hello"} 723828682858 (674.12 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 90311.8 (25h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1020392
telemt_connections_bad_total 18062
telemt_handshake_timeouts_total 13376
telemt_upstream_connect_attempt_total 22413
telemt_upstream_connect_success_total 21803
telemt_upstream_connect_fail_total 610
telemt_upstream_connect_attempts_per_request{bucket="1"} 22413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11329
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 610
telemt_me_keepalive_timeout_total 1723
telemt_me_reconnect_attempts_total 78226
telemt_me_reconnect_success_total 17285
telemt_me_reader_eof_total 19599
telemt_me_idle_close_by_peer_total 19598
telemt_me_route_drop_no_conn_total 397011
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 943680
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2551
telemt_desync_full_logged_total 796
telemt_desync_suppressed_total 1755
telemt_desync_frames_bucket_total{bucket="1_2"} 886
telemt_desync_frames_bucket_total{bucket="3_10"} 929
telemt_desync_frames_bucket_total{bucket="gt_10"} 736
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 19347
telemt_me_refill_failed_total 1899
telemt_me_writer_restored_same_endpoint_total 17280
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 2062
telemt_user_connections_total{user="hello"} 943617
telemt_user_connections_current{user="hello"} 776
telemt_user_octets_from_client{user="hello"} 16726648440 (15.58 GB)
telemt_user_octets_to_client{user="hello"} 317163172216 (295.38 GB)
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 112
```