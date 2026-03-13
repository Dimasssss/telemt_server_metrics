# Server Metrics 2026-03-13 07:25:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 91598.6 (25h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2508324
telemt_connections_bad_total 36155
telemt_handshake_timeouts_total 26448
telemt_upstream_connect_attempt_total 17873
telemt_upstream_connect_success_total 17773
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 17873
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8531
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_timeout_total 1349
telemt_me_reconnect_attempts_total 22101
telemt_me_reconnect_success_total 13229
telemt_me_reader_eof_total 14263
telemt_me_idle_close_by_peer_total 14262
telemt_me_route_drop_no_conn_total 942893
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2301834
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10306
telemt_desync_full_logged_total 2669
telemt_desync_suppressed_total 7637
telemt_desync_frames_bucket_total{bucket="1_2"} 2638
telemt_desync_frames_bucket_total{bucket="3_10"} 3795
telemt_desync_frames_bucket_total{bucket="gt_10"} 3873
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 13691
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 13216
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 462
telemt_user_connections_total{user="hello"} 2301352
telemt_user_connections_current{user="hello"} 1599
telemt_user_octets_from_client{user="hello"} 33013730424 (30.75 GB)
telemt_user_octets_to_client{user="hello"} 776496877844 (723.17 GB)
telemt_user_unique_ips_current{user="hello"} 446
telemt_user_unique_ips_recent_window{user="hello"} 225
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 121219.1 (33h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1009739
telemt_connections_bad_total 12829
telemt_handshake_timeouts_total 55774
telemt_upstream_connect_attempt_total 30442
telemt_upstream_connect_success_total 30411
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 30442
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15698
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14623
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3606
telemt_me_reconnect_attempts_total 22872
telemt_me_reconnect_success_total 22752
telemt_me_reader_eof_total 24251
telemt_me_idle_close_by_peer_total 24251
telemt_me_route_drop_no_conn_total 318216
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 901417
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3922
telemt_desync_full_logged_total 1204
telemt_desync_suppressed_total 2718
telemt_desync_frames_bucket_total{bucket="1_2"} 1492
telemt_desync_frames_bucket_total{bucket="3_10"} 1258
telemt_desync_frames_bucket_total{bucket="gt_10"} 1172
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 22975
telemt_me_writer_restored_same_endpoint_total 22743
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 223
telemt_user_connections_total{user="hello"} 903343
telemt_user_connections_current{user="hello"} 592
telemt_user_octets_from_client{user="hello"} 13977895016 (13.02 GB)
telemt_user_octets_to_client{user="hello"} 340526711311 (317.14 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 121218.9 (33h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2046748
telemt_connections_bad_total 23360
telemt_handshake_timeouts_total 136992
telemt_upstream_connect_attempt_total 27931
telemt_upstream_connect_success_total 27921
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 27931
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13173
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1707
telemt_me_reconnect_attempts_total 22824
telemt_me_reconnect_success_total 21548
telemt_me_reader_eof_total 22825
telemt_me_idle_close_by_peer_total 22824
telemt_me_route_drop_no_conn_total 657425
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1620730
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5508
telemt_desync_full_logged_total 1707
telemt_desync_suppressed_total 3801
telemt_desync_frames_bucket_total{bucket="1_2"} 902
telemt_desync_frames_bucket_total{bucket="3_10"} 2004
telemt_desync_frames_bucket_total{bucket="gt_10"} 2602
telemt_pool_swap_total 115
telemt_me_writer_removed_unexpected_total 21757
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 21507
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 1620208
telemt_user_connections_current{user="hello"} 895
telemt_user_octets_from_client{user="hello"} 27163336560 (25.30 GB)
telemt_user_octets_to_client{user="hello"} 586237055289 (545.98 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 121219.3 (33h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1257890
telemt_connections_bad_total 14068
telemt_handshake_timeouts_total 81322
telemt_upstream_connect_attempt_total 40904
telemt_upstream_connect_success_total 38607
telemt_upstream_connect_fail_total 2160
telemt_upstream_connect_attempts_per_request{bucket="1"} 40630
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23609
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14907
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2159
telemt_me_keepalive_timeout_total 11434
telemt_me_reconnect_attempts_total 35659
telemt_me_reconnect_success_total 26721
telemt_me_reader_eof_total 28788
telemt_me_idle_close_by_peer_total 28781
telemt_me_route_drop_no_conn_total 453202
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1079206
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2115
telemt_desync_full_logged_total 686
telemt_desync_suppressed_total 1429
telemt_desync_frames_bucket_total{bucket="1_2"} 582
telemt_desync_frames_bucket_total{bucket="3_10"} 815
telemt_desync_frames_bucket_total{bucket="gt_10"} 718
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 27184
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 26697
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 463
telemt_user_connections_total{user="hello"} 1083957
telemt_user_connections_current{user="hello"} 599
telemt_user_octets_from_client{user="hello"} 16495011129 (15.36 GB)
telemt_user_octets_to_client{user="hello"} 429766002766 (400.25 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 121219.2 (33h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1418756
telemt_connections_bad_total 24151
telemt_handshake_timeouts_total 11728
telemt_upstream_connect_attempt_total 38459
telemt_upstream_connect_success_total 37992
telemt_upstream_connect_fail_total 467
telemt_upstream_connect_attempts_per_request{bucket="1"} 38459
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19288
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18503
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 185
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 467
telemt_me_keepalive_timeout_total 2093
telemt_me_reconnect_attempts_total 45712
telemt_me_reconnect_success_total 31974
telemt_me_reader_eof_total 33563
telemt_me_idle_close_by_peer_total 33563
telemt_me_seq_mismatch_total 44
telemt_me_route_drop_no_conn_total 522131
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1305531
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 48
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4663
telemt_desync_full_logged_total 1661
telemt_desync_suppressed_total 3002
telemt_desync_frames_bucket_total{bucket="1_2"} 1416
telemt_desync_frames_bucket_total{bucket="3_10"} 1502
telemt_desync_frames_bucket_total{bucket="gt_10"} 1745
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 32752
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 31918
telemt_me_writer_restored_fallback_total 56
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 778
telemt_user_connections_total{user="hello"} 1305341
telemt_user_connections_current{user="hello"} 875
telemt_user_octets_from_client{user="hello"} 16559410604 (15.42 GB)
telemt_user_octets_to_client{user="hello"} 447415585712 (416.69 GB)
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 125
```