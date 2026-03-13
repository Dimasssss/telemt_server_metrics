# Server Metrics 2026-03-13 10:13:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 101709.6 (28h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2937093
telemt_connections_bad_total 36442
telemt_handshake_timeouts_total 53082
telemt_upstream_connect_attempt_total 20028
telemt_upstream_connect_success_total 19919
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 20028
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9628
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 1428
telemt_me_reconnect_attempts_total 24949
telemt_me_reconnect_success_total 14880
telemt_me_reader_eof_total 16027
telemt_me_idle_close_by_peer_total 16026
telemt_me_route_drop_no_conn_total 1084446
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2677789
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11687
telemt_desync_full_logged_total 3023
telemt_desync_suppressed_total 8664
telemt_desync_frames_bucket_total{bucket="1_2"} 2997
telemt_desync_frames_bucket_total{bucket="3_10"} 4379
telemt_desync_frames_bucket_total{bucket="gt_10"} 4311
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 15402
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 14867
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 522
telemt_user_connections_total{user="hello"} 2677708
telemt_user_connections_current{user="hello"} 1707
telemt_user_octets_from_client{user="hello"} 36906022340 (34.37 GB)
telemt_user_octets_to_client{user="hello"} 870614852436 (810.82 GB)
telemt_user_unique_ips_current{user="hello"} 453
telemt_user_unique_ips_recent_window{user="hello"} 249
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 131329.7 (36h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1179797
telemt_connections_bad_total 15052
telemt_handshake_timeouts_total 106920
telemt_upstream_connect_attempt_total 32471
telemt_upstream_connect_success_total 32440
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 32471
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16712
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15638
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3770
telemt_me_reconnect_attempts_total 24420
telemt_me_reconnect_success_total 24293
telemt_me_reader_eof_total 25894
telemt_me_idle_close_by_peer_total 25894
telemt_me_route_drop_no_conn_total 364710
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1015445
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4480
telemt_desync_full_logged_total 1356
telemt_desync_suppressed_total 3124
telemt_desync_frames_bucket_total{bucket="1_2"} 1630
telemt_desync_frames_bucket_total{bucket="3_10"} 1482
telemt_desync_frames_bucket_total{bucket="gt_10"} 1368
telemt_pool_swap_total 135
telemt_me_writer_removed_unexpected_total 24531
telemt_me_writer_restored_same_endpoint_total 24284
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 238
telemt_user_connections_total{user="hello"} 1017380
telemt_user_connections_current{user="hello"} 289
telemt_user_octets_from_client{user="hello"} 15454301340 (14.39 GB)
telemt_user_octets_to_client{user="hello"} 371332946915 (345.83 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 131329.5 (36h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2280133
telemt_connections_bad_total 25078
telemt_handshake_timeouts_total 155675
telemt_upstream_connect_attempt_total 30002
telemt_upstream_connect_success_total 29992
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 30002
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15718
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14154
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1852
telemt_me_reconnect_attempts_total 24411
telemt_me_reconnect_success_total 23123
telemt_me_reader_eof_total 24496
telemt_me_idle_close_by_peer_total 24495
telemt_me_route_drop_no_conn_total 746450
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1827809
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6013
telemt_desync_full_logged_total 1922
telemt_desync_suppressed_total 4091
telemt_desync_frames_bucket_total{bucket="1_2"} 979
telemt_desync_frames_bucket_total{bucket="3_10"} 2191
telemt_desync_frames_bucket_total{bucket="gt_10"} 2843
telemt_pool_swap_total 123
telemt_me_writer_removed_unexpected_total 23355
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 23082
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 232
telemt_user_connections_total{user="hello"} 1827259
telemt_user_connections_current{user="hello"} 1061
telemt_user_octets_from_client{user="hello"} 31676361288 (29.50 GB)
telemt_user_octets_to_client{user="hello"} 657840278965 (612.66 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 287
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 131329.8 (36h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1442647
telemt_connections_bad_total 14238
telemt_handshake_timeouts_total 89768
telemt_upstream_connect_attempt_total 42979
telemt_upstream_connect_success_total 40671
telemt_upstream_connect_fail_total 2171
telemt_upstream_connect_attempts_per_request{bucket="1"} 42705
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24738
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15842
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2170
telemt_me_keepalive_timeout_total 11506
telemt_me_reconnect_attempts_total 37245
telemt_me_reconnect_success_total 28297
telemt_me_reader_eof_total 30464
telemt_me_idle_close_by_peer_total 30457
telemt_me_route_drop_no_conn_total 509376
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1205619
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2267
telemt_desync_full_logged_total 747
telemt_desync_suppressed_total 1520
telemt_desync_frames_bucket_total{bucket="1_2"} 633
telemt_desync_frames_bucket_total{bucket="3_10"} 866
telemt_desync_frames_bucket_total{bucket="gt_10"} 768
telemt_pool_swap_total 114
telemt_me_writer_removed_unexpected_total 28781
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 28273
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 484
telemt_user_connections_total{user="hello"} 1210373
telemt_user_connections_current{user="hello"} 652
telemt_user_octets_from_client{user="hello"} 18367744473 (17.11 GB)
telemt_user_octets_to_client{user="hello"} 481220372902 (448.17 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 131329.6 (36h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1613751
telemt_connections_bad_total 36072
telemt_handshake_timeouts_total 13125
telemt_upstream_connect_attempt_total 42021
telemt_upstream_connect_success_total 41522
telemt_upstream_connect_fail_total 499
telemt_upstream_connect_attempts_per_request{bucket="1"} 42021
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20896
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20412
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 198
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 499
telemt_me_keepalive_timeout_total 2313
telemt_me_reconnect_attempts_total 52979
telemt_me_reconnect_success_total 35002
telemt_me_reader_eof_total 36781
telemt_me_idle_close_by_peer_total 36781
telemt_me_seq_mismatch_total 48
telemt_me_route_drop_no_conn_total 590796
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1467266
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 52
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 5145
telemt_desync_full_logged_total 1834
telemt_desync_suppressed_total 3311
telemt_desync_frames_bucket_total{bucket="1_2"} 1590
telemt_desync_frames_bucket_total{bucket="3_10"} 1664
telemt_desync_frames_bucket_total{bucket="gt_10"} 1891
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 35943
telemt_me_refill_failed_total 557
telemt_me_writer_restored_same_endpoint_total 34941
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 941
telemt_user_connections_total{user="hello"} 1467062
telemt_user_connections_current{user="hello"} 649
telemt_user_octets_from_client{user="hello"} 18764759316 (17.48 GB)
telemt_user_octets_to_client{user="hello"} 513244732132 (478.00 GB)
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 73
```