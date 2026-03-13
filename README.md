# Server Metrics 2026-03-13 08:31:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 95580.2 (26h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2674265
telemt_connections_bad_total 36276
telemt_handshake_timeouts_total 29978
telemt_upstream_connect_attempt_total 18587
telemt_upstream_connect_success_total 18485
telemt_upstream_connect_fail_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 18587
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9564
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8872
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_timeout_total 1367
telemt_me_reconnect_attempts_total 22596
telemt_me_reconnect_success_total 13721
telemt_me_reader_eof_total 14786
telemt_me_idle_close_by_peer_total 14785
telemt_me_route_drop_no_conn_total 996565
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2447432
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11028
telemt_desync_full_logged_total 2849
telemt_desync_suppressed_total 8179
telemt_desync_frames_bucket_total{bucket="1_2"} 2835
telemt_desync_frames_bucket_total{bucket="3_10"} 4127
telemt_desync_frames_bucket_total{bucket="gt_10"} 4066
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 14190
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 13708
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 469
telemt_user_connections_total{user="hello"} 2447039
telemt_user_connections_current{user="hello"} 1746
telemt_user_octets_from_client{user="hello"} 34528196704 (32.16 GB)
telemt_user_octets_to_client{user="hello"} 812107482648 (756.33 GB)
telemt_user_unique_ips_current{user="hello"} 468
telemt_user_unique_ips_recent_window{user="hello"} 272
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 125200.8 (34h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1090086
telemt_connections_bad_total 13671
telemt_handshake_timeouts_total 88500
telemt_upstream_connect_attempt_total 31237
telemt_upstream_connect_success_total 31206
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 31237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16087
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15029
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3633
telemt_me_reconnect_attempts_total 23446
telemt_me_reconnect_success_total 23325
telemt_me_reader_eof_total 24857
telemt_me_idle_close_by_peer_total 24857
telemt_me_route_drop_no_conn_total 336118
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 947257
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4185
telemt_desync_full_logged_total 1277
telemt_desync_suppressed_total 2908
telemt_desync_frames_bucket_total{bucket="1_2"} 1543
telemt_desync_frames_bucket_total{bucket="3_10"} 1369
telemt_desync_frames_bucket_total{bucket="gt_10"} 1273
telemt_pool_swap_total 129
telemt_me_writer_removed_unexpected_total 23554
telemt_me_writer_restored_same_endpoint_total 23316
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 229
telemt_user_connections_total{user="hello"} 949189
telemt_user_connections_current{user="hello"} 630
telemt_user_octets_from_client{user="hello"} 14575874704 (13.57 GB)
telemt_user_octets_to_client{user="hello"} 352667044951 (328.45 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 125200.8 (34h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2132033
telemt_connections_bad_total 23673
telemt_handshake_timeouts_total 142812
telemt_upstream_connect_attempt_total 28762
telemt_upstream_connect_success_total 28752
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 28762
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15066
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13570
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1750
telemt_me_reconnect_attempts_total 23439
telemt_me_reconnect_success_total 22157
telemt_me_reader_eof_total 23467
telemt_me_idle_close_by_peer_total 23466
telemt_me_route_drop_no_conn_total 690264
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1698355
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5682
telemt_desync_full_logged_total 1800
telemt_desync_suppressed_total 3882
telemt_desync_frames_bucket_total{bucket="1_2"} 931
telemt_desync_frames_bucket_total{bucket="3_10"} 2077
telemt_desync_frames_bucket_total{bucket="gt_10"} 2674
telemt_pool_swap_total 119
telemt_me_writer_removed_unexpected_total 22373
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 22116
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 1697808
telemt_user_connections_current{user="hello"} 947
telemt_user_octets_from_client{user="hello"} 28370969524 (26.42 GB)
telemt_user_octets_to_client{user="hello"} 615323627305 (573.06 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 285
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 125201.3 (34h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1356606
telemt_connections_bad_total 14217
telemt_handshake_timeouts_total 83577
telemt_upstream_connect_attempt_total 41794
telemt_upstream_connect_success_total 39493
telemt_upstream_connect_fail_total 2164
telemt_upstream_connect_attempts_per_request{bucket="1"} 41520
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24086
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15316
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2163
telemt_me_keepalive_timeout_total 11449
telemt_me_reconnect_attempts_total 36329
telemt_me_reconnect_success_total 27389
telemt_me_reader_eof_total 29494
telemt_me_idle_close_by_peer_total 29487
telemt_me_route_drop_no_conn_total 475106
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1127702
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2189
telemt_desync_full_logged_total 713
telemt_desync_suppressed_total 1476
telemt_desync_frames_bucket_total{bucket="1_2"} 602
telemt_desync_frames_bucket_total{bucket="3_10"} 840
telemt_desync_frames_bucket_total{bucket="gt_10"} 747
telemt_pool_swap_total 107
telemt_me_writer_removed_unexpected_total 27860
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 27365
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 471
telemt_user_connections_total{user="hello"} 1132462
telemt_user_connections_current{user="hello"} 682
telemt_user_octets_from_client{user="hello"} 17094412745 (15.92 GB)
telemt_user_octets_to_client{user="hello"} 452541322678 (421.46 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 125201.0 (34h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1495671
telemt_connections_bad_total 30260
telemt_handshake_timeouts_total 12406
telemt_upstream_connect_attempt_total 39494
telemt_upstream_connect_success_total 39017
telemt_upstream_connect_fail_total 477
telemt_upstream_connect_attempts_per_request{bucket="1"} 39494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19800
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19012
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 189
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 477
telemt_me_keepalive_timeout_total 2144
telemt_me_reconnect_attempts_total 46525
telemt_me_reconnect_success_total 32783
telemt_me_reader_eof_total 34389
telemt_me_idle_close_by_peer_total 34389
telemt_me_seq_mismatch_total 46
telemt_me_route_drop_no_conn_total 547831
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1370874
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 50
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4805
telemt_desync_full_logged_total 1718
telemt_desync_suppressed_total 3087
telemt_desync_frames_bucket_total{bucket="1_2"} 1461
telemt_desync_frames_bucket_total{bucket="3_10"} 1554
telemt_desync_frames_bucket_total{bucket="gt_10"} 1790
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 33571
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 32725
telemt_me_writer_restored_fallback_total 58
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 788
telemt_user_connections_total{user="hello"} 1370678
telemt_user_connections_current{user="hello"} 1002
telemt_user_octets_from_client{user="hello"} 17499220624 (16.30 GB)
telemt_user_octets_to_client{user="hello"} 476143587856 (443.44 GB)
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 129
```