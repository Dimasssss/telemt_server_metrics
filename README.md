# Server Metrics 2026-03-12 19:26:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 48439.8 (13h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1711723
telemt_connections_bad_total 20540
telemt_handshake_timeouts_total 16943
telemt_upstream_connect_attempt_total 9519
telemt_upstream_connect_success_total 9465
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 9519
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4942
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4489
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 573
telemt_me_reconnect_attempts_total 15864
telemt_me_reconnect_success_total 7018
telemt_me_reader_eof_total 7596
telemt_me_idle_close_by_peer_total 7595
telemt_me_route_drop_no_conn_total 670909
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1599499
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8072
telemt_desync_full_logged_total 2068
telemt_desync_suppressed_total 6004
telemt_desync_frames_bucket_total{bucket="1_2"} 2104
telemt_desync_frames_bucket_total{bucket="3_10"} 2912
telemt_desync_frames_bucket_total{bucket="gt_10"} 3056
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 7394
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 7005
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 376
telemt_user_connections_total{user="hello"} 1598994
telemt_user_connections_current{user="hello"} 1380
telemt_user_octets_from_client{user="hello"} 24765336884 (23.06 GB)
telemt_user_octets_to_client{user="hello"} 544675687552 (507.27 GB)
telemt_user_unique_ips_current{user="hello"} 385
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 78060.6 (21h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 729355
telemt_connections_bad_total 9823
telemt_handshake_timeouts_total 29917
telemt_upstream_connect_attempt_total 19834
telemt_upstream_connect_success_total 19805
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 19834
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10494
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9228
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3371
telemt_me_reconnect_attempts_total 14338
telemt_me_reconnect_success_total 14252
telemt_me_reader_eof_total 15151
telemt_me_idle_close_by_peer_total 15151
telemt_me_route_drop_no_conn_total 233585
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 657334
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2854
telemt_desync_full_logged_total 874
telemt_desync_suppressed_total 1980
telemt_desync_frames_bucket_total{bucket="1_2"} 1120
telemt_desync_frames_bucket_total{bucket="3_10"} 932
telemt_desync_frames_bucket_total{bucket="gt_10"} 802
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 14402
telemt_me_writer_restored_same_endpoint_total 14243
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 659210
telemt_user_connections_current{user="hello"} 378
telemt_user_octets_from_client{user="hello"} 11206571532 (10.44 GB)
telemt_user_octets_to_client{user="hello"} 249352682303 (232.23 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 78060.3 (21h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1507894
telemt_connections_bad_total 7266
telemt_handshake_timeouts_total 103301
telemt_upstream_connect_attempt_total 18447
telemt_upstream_connect_success_total 18441
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 18446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9910
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8458
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1185
telemt_me_reconnect_attempts_total 15418
telemt_me_reconnect_success_total 14173
telemt_me_reader_eof_total 14949
telemt_me_idle_close_by_peer_total 14948
telemt_me_route_drop_no_conn_total 496406
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1154543
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4752
telemt_desync_full_logged_total 1465
telemt_desync_suppressed_total 3287
telemt_desync_frames_bucket_total{bucket="1_2"} 748
telemt_desync_frames_bucket_total{bucket="3_10"} 1721
telemt_desync_frames_bucket_total{bucket="gt_10"} 2283
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 14303
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 14132
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 1154400
telemt_user_connections_current{user="hello"} 728
telemt_user_octets_from_client{user="hello"} 18061471044 (16.82 GB)
telemt_user_octets_to_client{user="hello"} 428097084845 (398.70 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 78061.0 (21h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 920808
telemt_connections_bad_total 12961
telemt_handshake_timeouts_total 67734
telemt_upstream_connect_attempt_total 20051
telemt_upstream_connect_success_total 19970
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 20051
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11219
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8738
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 1639
telemt_me_reconnect_attempts_total 23793
telemt_me_reconnect_success_total 16068
telemt_me_reader_eof_total 17164
telemt_me_idle_close_by_peer_total 17164
telemt_me_route_drop_no_conn_total 326241
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 797374
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1745
telemt_desync_full_logged_total 584
telemt_desync_suppressed_total 1161
telemt_desync_frames_bucket_total{bucket="1_2"} 490
telemt_desync_frames_bucket_total{bucket="3_10"} 675
telemt_desync_frames_bucket_total{bucket="gt_10"} 580
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 16439
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 16047
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 371
telemt_user_connections_total{user="hello"} 796732
telemt_user_connections_current{user="hello"} 472
telemt_user_octets_from_client{user="hello"} 12313853576 (11.47 GB)
telemt_user_octets_to_client{user="hello"} 326627956952 (304.20 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 78060.8 (21h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1033725
telemt_connections_bad_total 12087
telemt_handshake_timeouts_total 8514
telemt_upstream_connect_attempt_total 24249
telemt_upstream_connect_success_total 23958
telemt_upstream_connect_fail_total 291
telemt_upstream_connect_attempts_per_request{bucket="1"} 24249
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11592
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 123
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 291
telemt_me_keepalive_timeout_total 1394
telemt_me_reconnect_attempts_total 31074
telemt_me_reconnect_success_total 20039
telemt_me_reader_eof_total 21064
telemt_me_idle_close_by_peer_total 21064
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 386734
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 947890
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3556
telemt_desync_full_logged_total 1245
telemt_desync_suppressed_total 2311
telemt_desync_frames_bucket_total{bucket="1_2"} 1012
telemt_desync_frames_bucket_total{bucket="3_10"} 1185
telemt_desync_frames_bucket_total{bucket="gt_10"} 1359
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 20610
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 19995
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 571
telemt_user_connections_total{user="hello"} 947760
telemt_user_connections_current{user="hello"} 641
telemt_user_octets_from_client{user="hello"} 11763588988 (10.96 GB)
telemt_user_octets_to_client{user="hello"} 321080426288 (299.03 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 102
```