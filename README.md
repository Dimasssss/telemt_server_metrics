# Server Metrics 2026-03-14 09:34:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 185734.0 (51h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5297603
telemt_connections_bad_total 50563
telemt_handshake_timeouts_total 118682
telemt_upstream_connect_attempt_total 38968
telemt_upstream_connect_success_total 38716
telemt_upstream_connect_fail_total 252
telemt_upstream_connect_attempts_per_request{bucket="1"} 38968
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17566
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 252
telemt_me_keepalive_timeout_total 7511
telemt_me_reconnect_attempts_total 38356
telemt_me_reconnect_success_total 27141
telemt_me_reader_eof_total 29125
telemt_me_idle_close_by_peer_total 29124
telemt_me_route_drop_no_conn_total 2002708
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4853791
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 18574
telemt_desync_full_logged_total 5072
telemt_desync_suppressed_total 13502
telemt_desync_frames_bucket_total{bucket="1_2"} 4575
telemt_desync_frames_bucket_total{bucket="3_10"} 7081
telemt_desync_frames_bucket_total{bucket="gt_10"} 6918
telemt_pool_swap_total 161
telemt_me_writer_removed_unexpected_total 27889
telemt_me_refill_failed_total 345
telemt_me_writer_restored_same_endpoint_total 27128
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 748
telemt_user_connections_total{user="hello"} 4855266
telemt_user_connections_current{user="hello"} 1629
telemt_user_octets_from_client{user="hello"} 74382074568 (69.27 GB)
telemt_user_octets_to_client{user="hello"} 1551041515821 (1.41 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 471
telemt_user_unique_ips_recent_window{user="hello"} 232
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 85397.7 (23h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 953421
telemt_connections_bad_total 54895
telemt_handshake_timeouts_total 19466
telemt_upstream_connect_attempt_total 22579
telemt_upstream_connect_success_total 22291
telemt_upstream_connect_fail_total 288
telemt_upstream_connect_attempts_per_request{bucket="1"} 22579
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12118
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9885
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 41
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 247
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 288
telemt_me_keepalive_timeout_total 2218
telemt_me_reconnect_attempts_total 25896
telemt_me_reconnect_success_total 16025
telemt_me_reader_eof_total 17183
telemt_me_idle_close_by_peer_total 17182
telemt_me_route_drop_no_conn_total 318579
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 776348
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2183
telemt_desync_full_logged_total 687
telemt_desync_suppressed_total 1496
telemt_desync_frames_bucket_total{bucket="1_2"} 496
telemt_desync_frames_bucket_total{bucket="3_10"} 937
telemt_desync_frames_bucket_total{bucket="gt_10"} 750
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 16562
telemt_me_refill_failed_total 302
telemt_me_writer_restored_same_endpoint_total 16017
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 537
telemt_user_connections_total{user="hello"} 778245
telemt_user_connections_current{user="hello"} 621
telemt_user_octets_from_client{user="hello"} 8267773377 (7.70 GB)
telemt_user_octets_to_client{user="hello"} 268747421420 (250.29 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 215354.3 (59h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3772810
telemt_connections_bad_total 44530
telemt_handshake_timeouts_total 249079
telemt_upstream_connect_attempt_total 48629
telemt_upstream_connect_success_total 48608
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 48629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25677
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22676
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 248
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10899
telemt_me_reconnect_attempts_total 42559
telemt_me_reconnect_success_total 37563
telemt_me_reader_eof_total 39888
telemt_me_idle_close_by_peer_total 39887
telemt_me_route_drop_no_conn_total 1296268
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3151228
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10185
telemt_desync_full_logged_total 3461
telemt_desync_suppressed_total 6724
telemt_desync_frames_bucket_total{bucket="1_2"} 1821
telemt_desync_frames_bucket_total{bucket="3_10"} 3697
telemt_desync_frames_bucket_total{bucket="gt_10"} 4667
telemt_pool_swap_total 202
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 38086
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 37522
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 523
telemt_user_connections_total{user="hello"} 3150404
telemt_user_connections_current{user="hello"} 871
telemt_user_octets_from_client{user="hello"} 53377008796 (49.71 GB)
telemt_user_octets_to_client{user="hello"} 1129262274801 (1.03 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 215357.0 (59h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2493595
telemt_connections_bad_total 23378
telemt_handshake_timeouts_total 309796
telemt_upstream_connect_attempt_total 66708
telemt_upstream_connect_success_total 64209
telemt_upstream_connect_fail_total 2362
telemt_upstream_connect_attempts_per_request{bucket="1"} 66434
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38324
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25719
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2361
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20623
telemt_me_reconnect_attempts_total 58108
telemt_me_reconnect_success_total 46456
telemt_me_reader_eof_total 49813
telemt_me_idle_close_by_peer_total 49806
telemt_me_route_drop_no_conn_total 834955
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1956839
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4025
telemt_desync_full_logged_total 1317
telemt_desync_suppressed_total 2708
telemt_desync_frames_bucket_total{bucket="1_2"} 1131
telemt_desync_frames_bucket_total{bucket="3_10"} 1645
telemt_desync_frames_bucket_total{bucket="gt_10"} 1249
telemt_pool_swap_total 188
telemt_me_writer_removed_unexpected_total 47222
telemt_me_refill_failed_total 355
telemt_me_writer_restored_same_endpoint_total 46432
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 766
telemt_user_connections_total{user="hello"} 1963012
telemt_user_connections_current{user="hello"} 384
telemt_user_octets_from_client{user="hello"} 29377198243 (27.36 GB)
telemt_user_octets_to_client{user="hello"} 709793115834 (661.05 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 84790.4 (23h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 937903
telemt_connections_bad_total 13724
telemt_handshake_timeouts_total 12277
telemt_upstream_connect_attempt_total 21516
telemt_upstream_connect_success_total 20938
telemt_upstream_connect_fail_total 578
telemt_upstream_connect_attempts_per_request{bucket="1"} 21516
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10004
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10908
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 578
telemt_me_keepalive_timeout_total 1679
telemt_me_reconnect_attempts_total 68896
telemt_me_reconnect_success_total 16693
telemt_me_reader_eof_total 18733
telemt_me_idle_close_by_peer_total 18732
telemt_me_route_drop_no_conn_total 359219
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 870531
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2305
telemt_desync_full_logged_total 718
telemt_desync_suppressed_total 1587
telemt_desync_frames_bucket_total{bucket="1_2"} 761
telemt_desync_frames_bucket_total{bucket="3_10"} 868
telemt_desync_frames_bucket_total{bucket="gt_10"} 676
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 18479
telemt_me_refill_failed_total 1626
telemt_me_writer_restored_same_endpoint_total 16688
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1786
telemt_user_connections_total{user="hello"} 870474
telemt_user_connections_current{user="hello"} 831
telemt_user_octets_from_client{user="hello"} 15535045184 (14.47 GB)
telemt_user_octets_to_client{user="hello"} 293688628784 (273.52 GB)
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 104
```