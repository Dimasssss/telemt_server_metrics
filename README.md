# Server Metrics 2026-03-14 11:52:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 194017.2 (53h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5612285
telemt_connections_bad_total 58748
telemt_handshake_timeouts_total 123624
telemt_upstream_connect_attempt_total 40628
telemt_upstream_connect_success_total 40368
telemt_upstream_connect_fail_total 260
telemt_upstream_connect_attempts_per_request{bucket="1"} 40628
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21866
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18343
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 260
telemt_me_keepalive_timeout_total 7841
telemt_me_reconnect_attempts_total 44753
telemt_me_reconnect_success_total 28381
telemt_me_reader_eof_total 30557
telemt_me_idle_close_by_peer_total 30556
telemt_me_route_drop_no_conn_total 2123552
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5148116
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19828
telemt_desync_full_logged_total 5412
telemt_desync_suppressed_total 14416
telemt_desync_frames_bucket_total{bucket="1_2"} 4802
telemt_desync_frames_bucket_total{bucket="3_10"} 7570
telemt_desync_frames_bucket_total{bucket="gt_10"} 7456
telemt_pool_swap_total 164
telemt_me_writer_removed_unexpected_total 29306
telemt_me_refill_failed_total 506
telemt_me_writer_restored_same_endpoint_total 28368
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 925
telemt_user_connections_total{user="hello"} 5149560
telemt_user_connections_current{user="hello"} 1786
telemt_user_octets_from_client{user="hello"} 79866303332 (74.38 GB)
telemt_user_octets_to_client{user="hello"} 1639503993441 (1.49 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 469
telemt_user_unique_ips_recent_window{user="hello"} 241
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 93681.1 (26h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1074619
telemt_connections_bad_total 58904
telemt_handshake_timeouts_total 24691
telemt_upstream_connect_attempt_total 24344
telemt_upstream_connect_success_total 24043
telemt_upstream_connect_fail_total 301
telemt_upstream_connect_attempts_per_request{bucket="1"} 24344
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13096
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10636
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 263
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 301
telemt_me_keepalive_timeout_total 2400
telemt_me_reconnect_attempts_total 32344
telemt_me_reconnect_success_total 17344
telemt_me_reader_eof_total 18703
telemt_me_idle_close_by_peer_total 18702
telemt_me_route_drop_no_conn_total 362490
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 883718
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2452
telemt_desync_full_logged_total 770
telemt_desync_suppressed_total 1682
telemt_desync_frames_bucket_total{bucket="1_2"} 627
telemt_desync_frames_bucket_total{bucket="3_10"} 1022
telemt_desync_frames_bucket_total{bucket="gt_10"} 803
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18058
telemt_me_refill_failed_total 462
telemt_me_writer_restored_same_endpoint_total 17336
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 714
telemt_user_connections_total{user="hello"} 885631
telemt_user_connections_current{user="hello"} 754
telemt_user_octets_from_client{user="hello"} 9695054849 (9.03 GB)
telemt_user_octets_to_client{user="hello"} 312473126428 (291.01 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 223637.8 (62h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3979499
telemt_connections_bad_total 46189
telemt_handshake_timeouts_total 269397
telemt_upstream_connect_attempt_total 50443
telemt_upstream_connect_success_total 50422
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 50443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26616
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23540
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 259
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 11254
telemt_me_reconnect_attempts_total 44960
telemt_me_reconnect_success_total 38959
telemt_me_reader_eof_total 41382
telemt_me_idle_close_by_peer_total 41380
telemt_me_route_drop_no_conn_total 1367300
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3328700
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10708
telemt_desync_full_logged_total 3618
telemt_desync_suppressed_total 7090
telemt_desync_frames_bucket_total{bucket="1_2"} 1950
telemt_desync_frames_bucket_total{bucket="3_10"} 3874
telemt_desync_frames_bucket_total{bucket="gt_10"} 4884
telemt_pool_swap_total 207
telemt_pool_stale_pick_total 4
telemt_me_writer_removed_unexpected_total 39535
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 38918
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 576
telemt_user_connections_total{user="hello"} 3327843
telemt_user_connections_current{user="hello"} 995
telemt_user_octets_from_client{user="hello"} 56521041092 (52.64 GB)
telemt_user_octets_to_client{user="hello"} 1191694248849 (1.08 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 289
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 223640.3 (62h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2606341
telemt_connections_bad_total 23507
telemt_handshake_timeouts_total 335040
telemt_upstream_connect_attempt_total 69084
telemt_upstream_connect_success_total 66577
telemt_upstream_connect_fail_total 2370
telemt_upstream_connect_attempts_per_request{bucket="1"} 68810
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39640
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26771
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2369
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20959
telemt_me_reconnect_attempts_total 61191
telemt_me_reconnect_success_total 48411
telemt_me_reader_eof_total 51873
telemt_me_idle_close_by_peer_total 51865
telemt_me_route_drop_no_conn_total 866439
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2037946
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4115
telemt_desync_full_logged_total 1353
telemt_desync_suppressed_total 2762
telemt_desync_frames_bucket_total{bucket="1_2"} 1171
telemt_desync_frames_bucket_total{bucket="3_10"} 1681
telemt_desync_frames_bucket_total{bucket="gt_10"} 1263
telemt_pool_swap_total 192
telemt_me_writer_removed_unexpected_total 49231
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 48386
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 820
telemt_user_connections_total{user="hello"} 2044336
telemt_user_connections_current{user="hello"} 432
telemt_user_octets_from_client{user="hello"} 30287211819 (28.21 GB)
telemt_user_octets_to_client{user="hello"} 729752953742 (679.64 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 93073.8 (25h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1059569
telemt_connections_bad_total 18092
telemt_handshake_timeouts_total 13740
telemt_upstream_connect_attempt_total 22744
telemt_upstream_connect_success_total 22118
telemt_upstream_connect_fail_total 626
telemt_upstream_connect_attempts_per_request{bucket="1"} 22744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10607
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11485
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 626
telemt_me_keepalive_timeout_total 1789
telemt_me_reconnect_attempts_total 82507
telemt_me_reconnect_success_total 17469
telemt_me_reader_eof_total 19909
telemt_me_idle_close_by_peer_total 19908
telemt_me_route_drop_no_conn_total 428615
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 980967
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2630
telemt_desync_full_logged_total 823
telemt_desync_suppressed_total 1807
telemt_desync_frames_bucket_total{bucket="1_2"} 939
telemt_desync_frames_bucket_total{bucket="3_10"} 939
telemt_desync_frames_bucket_total{bucket="gt_10"} 752
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 19660
telemt_me_refill_failed_total 2027
telemt_me_writer_restored_same_endpoint_total 17464
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 2191
telemt_user_connections_total{user="hello"} 980166
telemt_user_connections_current{user="hello"} 669
telemt_user_octets_from_client{user="hello"} 17078517928 (15.91 GB)
telemt_user_octets_to_client{user="hello"} 330343455096 (307.66 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 94
```