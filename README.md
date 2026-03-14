# Server Metrics 2026-03-14 06:50:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 175902.9 (48h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4953887
telemt_connections_bad_total 40205
telemt_handshake_timeouts_total 113043
telemt_upstream_connect_attempt_total 36922
telemt_upstream_connect_success_total 36681
telemt_upstream_connect_fail_total 241
telemt_upstream_connect_attempts_per_request{bucket="1"} 36922
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19933
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16599
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 241
telemt_me_keepalive_timeout_total 7328
telemt_me_reconnect_attempts_total 35745
telemt_me_reconnect_success_total 25594
telemt_me_reader_eof_total 27467
telemt_me_idle_close_by_peer_total 27466
telemt_me_route_drop_no_conn_total 1875776
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4545832
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17379
telemt_desync_full_logged_total 4709
telemt_desync_suppressed_total 12670
telemt_desync_frames_bucket_total{bucket="1_2"} 4336
telemt_desync_frames_bucket_total{bucket="3_10"} 6619
telemt_desync_frames_bucket_total{bucket="gt_10"} 6424
telemt_pool_swap_total 155
telemt_me_writer_removed_unexpected_total 26278
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 25581
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 684
telemt_user_connections_total{user="hello"} 4547323
telemt_user_connections_current{user="hello"} 1405
telemt_user_octets_from_client{user="hello"} 66512662944 (61.94 GB)
telemt_user_octets_to_client{user="hello"} 1432325502601 (1.30 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 414
telemt_user_unique_ips_recent_window{user="hello"} 209
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 75566.7 (20h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 822620
telemt_connections_bad_total 53811
telemt_handshake_timeouts_total 15044
telemt_upstream_connect_attempt_total 20462
telemt_upstream_connect_success_total 20191
telemt_upstream_connect_fail_total 271
telemt_upstream_connect_attempts_per_request{bucket="1"} 20462
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11085
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8841
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 232
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 271
telemt_me_keepalive_timeout_total 2143
telemt_me_reconnect_attempts_total 17880
telemt_me_reconnect_success_total 14416
telemt_me_reader_eof_total 15321
telemt_me_idle_close_by_peer_total 15320
telemt_me_route_drop_no_conn_total 269952
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 654478
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1887
telemt_desync_full_logged_total 575
telemt_desync_suppressed_total 1312
telemt_desync_frames_bucket_total{bucket="1_2"} 387
telemt_desync_frames_bucket_total{bucket="3_10"} 853
telemt_desync_frames_bucket_total{bucket="gt_10"} 647
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 14730
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 14408
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 314
telemt_user_connections_total{user="hello"} 656394
telemt_user_connections_current{user="hello"} 497
telemt_user_octets_from_client{user="hello"} 6880753153 (6.41 GB)
telemt_user_octets_to_client{user="hello"} 222006940924 (206.76 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 205523.5 (57h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3557095
telemt_connections_bad_total 41688
telemt_handshake_timeouts_total 233760
telemt_upstream_connect_attempt_total 46447
telemt_upstream_connect_success_total 46426
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 46447
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21694
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 241
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10669
telemt_me_reconnect_attempts_total 40860
telemt_me_reconnect_success_total 35885
telemt_me_reader_eof_total 38121
telemt_me_idle_close_by_peer_total 38120
telemt_me_route_drop_no_conn_total 1215935
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2965312
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9782
telemt_desync_full_logged_total 3284
telemt_desync_suppressed_total 6498
telemt_desync_frames_bucket_total{bucket="1_2"} 1702
telemt_desync_frames_bucket_total{bucket="3_10"} 3537
telemt_desync_frames_bucket_total{bucket="gt_10"} 4543
telemt_pool_swap_total 195
telemt_me_writer_removed_unexpected_total 36383
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 35844
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 498
telemt_user_connections_total{user="hello"} 2964463
telemt_user_connections_current{user="hello"} 760
telemt_user_octets_from_client{user="hello"} 49460881472 (46.06 GB)
telemt_user_octets_to_client{user="hello"} 1058870923129 (986.15 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 205526.1 (57h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2371780
telemt_connections_bad_total 23300
telemt_handshake_timeouts_total 280793
telemt_upstream_connect_attempt_total 64032
telemt_upstream_connect_success_total 61543
telemt_upstream_connect_fail_total 2352
telemt_upstream_connect_attempts_per_request{bucket="1"} 63758
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36733
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24644
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2351
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20516
telemt_me_reconnect_attempts_total 53338
telemt_me_reconnect_success_total 44291
telemt_me_reader_eof_total 47489
telemt_me_idle_close_by_peer_total 47482
telemt_me_route_drop_no_conn_total 799231
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1870793
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3906
telemt_desync_full_logged_total 1266
telemt_desync_suppressed_total 2640
telemt_desync_frames_bucket_total{bucket="1_2"} 1063
telemt_desync_frames_bucket_total{bucket="3_10"} 1617
telemt_desync_frames_bucket_total{bucket="gt_10"} 1226
telemt_pool_swap_total 183
telemt_me_writer_removed_unexpected_total 44958
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 44267
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 667
telemt_user_connections_total{user="hello"} 1876849
telemt_user_connections_current{user="hello"} 373
telemt_user_octets_from_client{user="hello"} 28301812467 (26.36 GB)
telemt_user_octets_to_client{user="hello"} 690204717142 (642.80 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 74959.5 (20h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 795748
telemt_connections_bad_total 8105
telemt_handshake_timeouts_total 9374
telemt_upstream_connect_attempt_total 19080
telemt_upstream_connect_success_total 18564
telemt_upstream_connect_fail_total 516
telemt_upstream_connect_attempts_per_request{bucket="1"} 19080
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9683
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 516
telemt_me_keepalive_timeout_total 1574
telemt_me_reconnect_attempts_total 60121
telemt_me_reconnect_success_total 14815
telemt_me_reader_eof_total 16596
telemt_me_idle_close_by_peer_total 16595
telemt_me_route_drop_no_conn_total 306342
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 743393
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1809
telemt_desync_full_logged_total 578
telemt_desync_suppressed_total 1231
telemt_desync_frames_bucket_total{bucket="1_2"} 535
telemt_desync_frames_bucket_total{bucket="3_10"} 699
telemt_desync_frames_bucket_total{bucket="gt_10"} 575
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 16358
telemt_me_refill_failed_total 1411
telemt_me_writer_restored_same_endpoint_total 14810
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1543
telemt_user_connections_total{user="hello"} 743255
telemt_user_connections_current{user="hello"} 580
telemt_user_octets_from_client{user="hello"} 13190399392 (12.28 GB)
telemt_user_octets_to_client{user="hello"} 249918985324 (232.76 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 88
```