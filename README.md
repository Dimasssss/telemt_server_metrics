# Server Metrics 2026-03-14 08:42:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 182654.0 (50h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5176263
telemt_connections_bad_total 44337
telemt_handshake_timeouts_total 116743
telemt_upstream_connect_attempt_total 38390
telemt_upstream_connect_success_total 38140
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 38390
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17314
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_keepalive_timeout_total 7420
telemt_me_reconnect_attempts_total 37954
telemt_me_reconnect_success_total 26743
telemt_me_reader_eof_total 28700
telemt_me_idle_close_by_peer_total 28699
telemt_me_route_drop_no_conn_total 1960026
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4747301
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 18136
telemt_desync_full_logged_total 4940
telemt_desync_suppressed_total 13196
telemt_desync_frames_bucket_total{bucket="1_2"} 4503
telemt_desync_frames_bucket_total{bucket="3_10"} 6889
telemt_desync_frames_bucket_total{bucket="gt_10"} 6744
telemt_pool_swap_total 158
telemt_me_writer_removed_unexpected_total 27481
telemt_me_refill_failed_total 345
telemt_me_writer_restored_same_endpoint_total 26730
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 738
telemt_user_connections_total{user="hello"} 4748749
telemt_user_connections_current{user="hello"} 1484
telemt_user_octets_from_client{user="hello"} 72811693124 (67.81 GB)
telemt_user_octets_to_client{user="hello"} 1519563838901 (1.38 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 437
telemt_user_unique_ips_recent_window{user="hello"} 220
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 82317.9 (22h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 906662
telemt_connections_bad_total 54147
telemt_handshake_timeouts_total 17338
telemt_upstream_connect_attempt_total 22089
telemt_upstream_connect_success_total 21808
telemt_upstream_connect_fail_total 281
telemt_upstream_connect_attempts_per_request{bucket="1"} 22089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11861
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9665
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 243
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 281
telemt_me_keepalive_timeout_total 2180
telemt_me_reconnect_attempts_total 21516
telemt_me_reconnect_success_total 15678
telemt_me_reader_eof_total 16707
telemt_me_idle_close_by_peer_total 16706
telemt_me_route_drop_no_conn_total 301764
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 733589
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
telemt_me_writer_removed_unexpected_total 16086
telemt_me_refill_failed_total 176
telemt_me_writer_restored_same_endpoint_total 15670
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 408
telemt_user_connections_total{user="hello"} 735487
telemt_user_connections_current{user="hello"} 615
telemt_user_octets_from_client{user="hello"} 7773188837 (7.24 GB)
telemt_user_octets_to_client{user="hello"} 255167229736 (237.64 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 212274.7 (58h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3697316
telemt_connections_bad_total 43531
telemt_handshake_timeouts_total 243365
telemt_upstream_connect_attempt_total 47865
telemt_upstream_connect_success_total 47844
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 47865
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25274
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22317
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 246
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10793
telemt_me_reconnect_attempts_total 41971
telemt_me_reconnect_success_total 36984
telemt_me_reader_eof_total 39274
telemt_me_idle_close_by_peer_total 39273
telemt_me_route_drop_no_conn_total 1268493
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3086864
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10089
telemt_desync_full_logged_total 3414
telemt_desync_suppressed_total 6675
telemt_desync_frames_bucket_total{bucket="1_2"} 1782
telemt_desync_frames_bucket_total{bucket="3_10"} 3657
telemt_desync_frames_bucket_total{bucket="gt_10"} 4650
telemt_pool_swap_total 200
telemt_me_writer_removed_unexpected_total 37496
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 36943
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 512
telemt_user_connections_total{user="hello"} 3086007
telemt_user_connections_current{user="hello"} 848
telemt_user_octets_from_client{user="hello"} 52380468232 (48.78 GB)
telemt_user_octets_to_client{user="hello"} 1102914420341 (1.00 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 261
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 212277.3 (58h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2452320
telemt_connections_bad_total 23350
telemt_handshake_timeouts_total 299603
telemt_upstream_connect_attempt_total 66019
telemt_upstream_connect_success_total 63522
telemt_upstream_connect_fail_total 2360
telemt_upstream_connect_attempts_per_request{bucket="1"} 65745
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25434
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2359
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20581
telemt_me_reconnect_attempts_total 55038
telemt_me_reconnect_success_total 45952
telemt_me_reader_eof_total 49205
telemt_me_idle_close_by_peer_total 49198
telemt_me_route_drop_no_conn_total 821575
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1928363
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3968
telemt_desync_full_logged_total 1293
telemt_desync_suppressed_total 2675
telemt_desync_frames_bucket_total{bucket="1_2"} 1097
telemt_desync_frames_bucket_total{bucket="3_10"} 1630
telemt_desync_frames_bucket_total{bucket="gt_10"} 1241
telemt_pool_swap_total 186
telemt_me_writer_removed_unexpected_total 46629
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 45928
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 677
telemt_user_connections_total{user="hello"} 1934501
telemt_user_connections_current{user="hello"} 464
telemt_user_octets_from_client{user="hello"} 28944415079 (26.96 GB)
telemt_user_octets_to_client{user="hello"} 702943037326 (654.67 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 81710.4 (22h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 891069
telemt_connections_bad_total 11148
telemt_handshake_timeouts_total 10651
telemt_upstream_connect_attempt_total 20582
telemt_upstream_connect_success_total 20033
telemt_upstream_connect_fail_total 549
telemt_upstream_connect_attempts_per_request{bucket="1"} 20582
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9593
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10414
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 549
telemt_me_keepalive_timeout_total 1636
telemt_me_reconnect_attempts_total 66506
telemt_me_reconnect_success_total 15972
telemt_me_reader_eof_total 17947
telemt_me_idle_close_by_peer_total 17946
telemt_me_route_drop_no_conn_total 340292
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 829845
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2134
telemt_desync_full_logged_total 672
telemt_desync_suppressed_total 1462
telemt_desync_frames_bucket_total{bucket="1_2"} 686
telemt_desync_frames_bucket_total{bucket="3_10"} 810
telemt_desync_frames_bucket_total{bucket="gt_10"} 638
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 17693
telemt_me_refill_failed_total 1574
telemt_me_writer_restored_same_endpoint_total 15967
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1721
telemt_user_connections_total{user="hello"} 829709
telemt_user_connections_current{user="hello"} 683
telemt_user_octets_from_client{user="hello"} 15066508260 (14.03 GB)
telemt_user_octets_to_client{user="hello"} 282068445784 (262.70 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 83
```