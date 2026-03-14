# Server Metrics 2026-03-14 09:13:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 184500.9 (51h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5249941
telemt_connections_bad_total 48210
telemt_handshake_timeouts_total 118170
telemt_upstream_connect_attempt_total 38720
telemt_upstream_connect_success_total 38469
telemt_upstream_connect_fail_total 251
telemt_upstream_connect_attempts_per_request{bucket="1"} 38720
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20861
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17455
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 251
telemt_me_keepalive_timeout_total 7502
telemt_me_reconnect_attempts_total 38196
telemt_me_reconnect_success_total 26983
telemt_me_reader_eof_total 28951
telemt_me_idle_close_by_peer_total 28950
telemt_me_route_drop_no_conn_total 1985860
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4810207
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 18404
telemt_desync_full_logged_total 5024
telemt_desync_suppressed_total 13380
telemt_desync_frames_bucket_total{bucket="1_2"} 4548
telemt_desync_frames_bucket_total{bucket="3_10"} 7002
telemt_desync_frames_bucket_total{bucket="gt_10"} 6854
telemt_pool_swap_total 159
telemt_me_writer_removed_unexpected_total 27727
telemt_me_refill_failed_total 345
telemt_me_writer_restored_same_endpoint_total 26970
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 744
telemt_user_connections_total{user="hello"} 4811688
telemt_user_connections_current{user="hello"} 1646
telemt_user_octets_from_client{user="hello"} 73698616420 (68.64 GB)
telemt_user_octets_to_client{user="hello"} 1537614111677 (1.40 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 455
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 84173.4 (23h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 934216
telemt_connections_bad_total 54254
telemt_handshake_timeouts_total 18546
telemt_upstream_connect_attempt_total 22408
telemt_upstream_connect_success_total 22120
telemt_upstream_connect_fail_total 288
telemt_upstream_connect_attempts_per_request{bucket="1"} 22408
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12039
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9796
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 246
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 288
telemt_me_keepalive_timeout_total 2211
telemt_me_reconnect_attempts_total 24458
telemt_me_reconnect_success_total 15899
telemt_me_reader_eof_total 17016
telemt_me_idle_close_by_peer_total 17015
telemt_me_route_drop_no_conn_total 312287
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 759158
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2173
telemt_desync_full_logged_total 681
telemt_desync_suppressed_total 1492
telemt_desync_frames_bucket_total{bucket="1_2"} 494
telemt_desync_frames_bucket_total{bucket="3_10"} 933
telemt_desync_frames_bucket_total{bucket="gt_10"} 746
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 16395
telemt_me_refill_failed_total 261
telemt_me_writer_restored_same_endpoint_total 15891
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 496
telemt_user_connections_total{user="hello"} 761057
telemt_user_connections_current{user="hello"} 548
telemt_user_octets_from_client{user="hello"} 8113399549 (7.56 GB)
telemt_user_octets_to_client{user="hello"} 262936728100 (244.88 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 214121.4 (59h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3742884
telemt_connections_bad_total 44506
telemt_handshake_timeouts_total 247506
telemt_upstream_connect_attempt_total 48323
telemt_upstream_connect_success_total 48302
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 48323
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25507
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22541
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 247
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10878
telemt_me_reconnect_attempts_total 42341
telemt_me_reconnect_success_total 37351
telemt_me_reader_eof_total 39662
telemt_me_idle_close_by_peer_total 39661
telemt_me_route_drop_no_conn_total 1285003
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3124845
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10127
telemt_desync_full_logged_total 3440
telemt_desync_suppressed_total 6687
telemt_desync_frames_bucket_total{bucket="1_2"} 1797
telemt_desync_frames_bucket_total{bucket="3_10"} 3673
telemt_desync_frames_bucket_total{bucket="gt_10"} 4657
telemt_pool_swap_total 201
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 37869
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 37310
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 518
telemt_user_connections_total{user="hello"} 3123996
telemt_user_connections_current{user="hello"} 867
telemt_user_octets_from_client{user="hello"} 52770670088 (49.15 GB)
telemt_user_octets_to_client{user="hello"} 1115784609985 (1.01 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 263
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 214124.1 (59h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2477147
telemt_connections_bad_total 23368
telemt_handshake_timeouts_total 305646
telemt_upstream_connect_attempt_total 66421
telemt_upstream_connect_success_total 63923
telemt_upstream_connect_fail_total 2361
telemt_upstream_connect_attempts_per_request{bucket="1"} 66147
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38177
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25580
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2360
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20621
telemt_me_reconnect_attempts_total 57908
telemt_me_reconnect_success_total 46262
telemt_me_reader_eof_total 49599
telemt_me_idle_close_by_peer_total 49592
telemt_me_route_drop_no_conn_total 829047
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1945648
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4002
telemt_desync_full_logged_total 1306
telemt_desync_suppressed_total 2696
telemt_desync_frames_bucket_total{bucket="1_2"} 1122
telemt_desync_frames_bucket_total{bucket="3_10"} 1636
telemt_desync_frames_bucket_total{bucket="gt_10"} 1244
telemt_pool_swap_total 186
telemt_me_writer_removed_unexpected_total 47023
telemt_me_refill_failed_total 355
telemt_me_writer_restored_same_endpoint_total 46238
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 761
telemt_user_connections_total{user="hello"} 1951807
telemt_user_connections_current{user="hello"} 521
telemt_user_octets_from_client{user="hello"} 29213388339 (27.21 GB)
telemt_user_octets_to_client{user="hello"} 706891163418 (658.34 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 83557.6 (23h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 918611
telemt_connections_bad_total 12744
telemt_handshake_timeouts_total 11685
telemt_upstream_connect_attempt_total 21139
telemt_upstream_connect_success_total 20577
telemt_upstream_connect_fail_total 562
telemt_upstream_connect_attempts_per_request{bucket="1"} 21139
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9869
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10682
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 562
telemt_me_keepalive_timeout_total 1659
telemt_me_reconnect_attempts_total 66962
telemt_me_reconnect_success_total 16425
telemt_me_reader_eof_total 18407
telemt_me_idle_close_by_peer_total 18406
telemt_me_route_drop_no_conn_total 351267
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 853668
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2246
telemt_desync_full_logged_total 703
telemt_desync_suppressed_total 1543
telemt_desync_frames_bucket_total{bucket="1_2"} 726
telemt_desync_frames_bucket_total{bucket="3_10"} 857
telemt_desync_frames_bucket_total{bucket="gt_10"} 663
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 18153
telemt_me_refill_failed_total 1574
telemt_me_writer_restored_same_endpoint_total 16420
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1728
telemt_user_connections_total{user="hello"} 853593
telemt_user_connections_current{user="hello"} 720
telemt_user_octets_from_client{user="hello"} 15303563396 (14.25 GB)
telemt_user_octets_to_client{user="hello"} 289921561396 (270.01 GB)
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 91
```