# Server Metrics 2026-03-14 05:07:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 169759.2 (47h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4805938
telemt_connections_bad_total 39906
telemt_handshake_timeouts_total 110241
telemt_upstream_connect_attempt_total 35774
telemt_upstream_connect_success_total 35539
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 35774
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19349
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16043
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_keepalive_timeout_total 7304
telemt_me_reconnect_attempts_total 34906
telemt_me_reconnect_success_total 24761
telemt_me_reader_eof_total 26574
telemt_me_idle_close_by_peer_total 26573
telemt_me_route_drop_no_conn_total 1820306
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4409253
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16964
telemt_desync_full_logged_total 4588
telemt_desync_suppressed_total 12376
telemt_desync_frames_bucket_total{bucket="1_2"} 4232
telemt_desync_frames_bucket_total{bucket="3_10"} 6474
telemt_desync_frames_bucket_total{bucket="gt_10"} 6258
telemt_pool_swap_total 148
telemt_me_writer_removed_unexpected_total 25428
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 24748
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 667
telemt_user_connections_total{user="hello"} 4410806
telemt_user_connections_current{user="hello"} 977
telemt_user_octets_from_client{user="hello"} 64387072412 (59.97 GB)
telemt_user_octets_to_client{user="hello"} 1389923044865 (1.26 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 304
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 69423.0 (19h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 758676
telemt_connections_bad_total 53055
telemt_handshake_timeouts_total 14062
telemt_upstream_connect_attempt_total 19085
telemt_upstream_connect_success_total 18818
telemt_upstream_connect_fail_total 266
telemt_upstream_connect_attempts_per_request{bucket="1"} 19084
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8156
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 223
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 266
telemt_me_keepalive_timeout_total 2109
telemt_me_reconnect_attempts_total 16767
telemt_me_reconnect_success_total 13310
telemt_me_reader_eof_total 14141
telemt_me_idle_close_by_peer_total 14140
telemt_me_route_drop_no_conn_total 249518
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 600961
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1785
telemt_desync_full_logged_total 529
telemt_desync_suppressed_total 1256
telemt_desync_frames_bucket_total{bucket="1_2"} 373
telemt_desync_frames_bucket_total{bucket="3_10"} 795
telemt_desync_frames_bucket_total{bucket="gt_10"} 617
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 13600
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 13302
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 290
telemt_user_connections_total{user="hello"} 602912
telemt_user_connections_current{user="hello"} 314
telemt_user_octets_from_client{user="hello"} 6434679933 (5.99 GB)
telemt_user_octets_to_client{user="hello"} 201057827524 (187.25 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 199379.8 (55h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3456104
telemt_connections_bad_total 37726
telemt_handshake_timeouts_total 228521
telemt_upstream_connect_attempt_total 45087
telemt_upstream_connect_success_total 45066
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 45087
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23724
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21095
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 240
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10627
telemt_me_reconnect_attempts_total 39807
telemt_me_reconnect_success_total 34837
telemt_me_reader_eof_total 37010
telemt_me_idle_close_by_peer_total 37009
telemt_me_route_drop_no_conn_total 1181819
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2879734
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9534
telemt_desync_full_logged_total 3203
telemt_desync_suppressed_total 6331
telemt_desync_frames_bucket_total{bucket="1_2"} 1651
telemt_desync_frames_bucket_total{bucket="3_10"} 3455
telemt_desync_frames_bucket_total{bucket="gt_10"} 4428
telemt_pool_swap_total 189
telemt_me_writer_removed_unexpected_total 35322
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 34796
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 485
telemt_user_connections_total{user="hello"} 2878948
telemt_user_connections_current{user="hello"} 465
telemt_user_octets_from_client{user="hello"} 45971611664 (42.81 GB)
telemt_user_octets_to_client{user="hello"} 1032433256801 (961.53 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 199382.3 (55h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2317435
telemt_connections_bad_total 23112
telemt_handshake_timeouts_total 263563
telemt_upstream_connect_attempt_total 62295
telemt_upstream_connect_success_total 59818
telemt_upstream_connect_fail_total 2340
telemt_upstream_connect_attempts_per_request{bucket="1"} 62021
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23930
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2339
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20470
telemt_me_reconnect_attempts_total 51917
telemt_me_reconnect_success_total 42876
telemt_me_reader_eof_total 45989
telemt_me_idle_close_by_peer_total 45982
telemt_me_route_drop_no_conn_total 785445
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1836553
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3884
telemt_desync_full_logged_total 1251
telemt_desync_suppressed_total 2633
telemt_desync_frames_bucket_total{bucket="1_2"} 1045
telemt_desync_frames_bucket_total{bucket="3_10"} 1614
telemt_desync_frames_bucket_total{bucket="gt_10"} 1225
telemt_pool_swap_total 177
telemt_me_writer_removed_unexpected_total 43531
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 42852
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 655
telemt_user_connections_total{user="hello"} 1842526
telemt_user_connections_current{user="hello"} 296
telemt_user_octets_from_client{user="hello"} 27923725319 (26.01 GB)
telemt_user_octets_to_client{user="hello"} 675776394418 (629.37 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 68815.9 (19h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 743769
telemt_connections_bad_total 8006
telemt_handshake_timeouts_total 8914
telemt_upstream_connect_attempt_total 17856
telemt_upstream_connect_success_total 17388
telemt_upstream_connect_fail_total 468
telemt_upstream_connect_attempts_per_request{bucket="1"} 17856
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8210
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9152
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 468
telemt_me_keepalive_timeout_total 1541
telemt_me_reconnect_attempts_total 52709
telemt_me_reconnect_success_total 13947
telemt_me_reader_eof_total 15507
telemt_me_idle_close_by_peer_total 15506
telemt_me_route_drop_no_conn_total 284195
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 694179
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1746
telemt_desync_full_logged_total 554
telemt_desync_suppressed_total 1192
telemt_desync_frames_bucket_total{bucket="1_2"} 518
telemt_desync_frames_bucket_total{bucket="3_10"} 683
telemt_desync_frames_bucket_total{bucket="gt_10"} 545
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 15277
telemt_me_refill_failed_total 1207
telemt_me_writer_restored_same_endpoint_total 13942
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1330
telemt_user_connections_total{user="hello"} 694044
telemt_user_connections_current{user="hello"} 419
telemt_user_octets_from_client{user="hello"} 12517212764 (11.66 GB)
telemt_user_octets_to_client{user="hello"} 228233764064 (212.56 GB)
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 51
```