# Server Metrics 2026-03-12 18:24:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 44761.3 (12h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1604924
telemt_connections_bad_total 20489
telemt_handshake_timeouts_total 14909
telemt_upstream_connect_attempt_total 8919
telemt_upstream_connect_success_total 8868
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 8919
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4205
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 559
telemt_me_reconnect_attempts_total 15439
telemt_me_reconnect_success_total 6594
telemt_me_reader_eof_total 7143
telemt_me_idle_close_by_peer_total 7142
telemt_me_route_drop_no_conn_total 626697
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1503196
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7691
telemt_desync_full_logged_total 1952
telemt_desync_suppressed_total 5739
telemt_desync_frames_bucket_total{bucket="1_2"} 1998
telemt_desync_frames_bucket_total{bucket="3_10"} 2799
telemt_desync_frames_bucket_total{bucket="gt_10"} 2894
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 6964
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 6581
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 370
telemt_user_connections_total{user="hello"} 1502686
telemt_user_connections_current{user="hello"} 1638
telemt_user_octets_from_client{user="hello"} 23296750312 (21.70 GB)
telemt_user_octets_to_client{user="hello"} 500314380372 (465.95 GB)
telemt_user_unique_ips_current{user="hello"} 430
telemt_user_unique_ips_recent_window{user="hello"} 244
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 74381.6 (20h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 691716
telemt_connections_bad_total 8943
telemt_handshake_timeouts_total 29323
telemt_upstream_connect_attempt_total 19106
telemt_upstream_connect_success_total 19077
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 19106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10117
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8884
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3362
telemt_me_reconnect_attempts_total 13782
telemt_me_reconnect_success_total 13697
telemt_me_reader_eof_total 14558
telemt_me_idle_close_by_peer_total 14558
telemt_me_route_drop_no_conn_total 220492
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 622607
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2730
telemt_desync_full_logged_total 832
telemt_desync_suppressed_total 1898
telemt_desync_frames_bucket_total{bucket="1_2"} 1101
telemt_desync_frames_bucket_total{bucket="3_10"} 895
telemt_desync_frames_bucket_total{bucket="gt_10"} 734
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 13841
telemt_me_writer_restored_same_endpoint_total 13688
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 624487
telemt_user_connections_current{user="hello"} 510
telemt_user_octets_from_client{user="hello"} 9486970436 (8.84 GB)
telemt_user_octets_to_client{user="hello"} 235041757955 (218.90 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 74381.6 (20h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1434996
telemt_connections_bad_total 6982
telemt_handshake_timeouts_total 100029
telemt_upstream_connect_attempt_total 17713
telemt_upstream_connect_success_total 17708
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 17713
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9523
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8114
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1172
telemt_me_reconnect_attempts_total 14857
telemt_me_reconnect_success_total 13613
telemt_me_reader_eof_total 14348
telemt_me_idle_close_by_peer_total 14347
telemt_me_route_drop_no_conn_total 470936
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1094793
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4640
telemt_desync_full_logged_total 1432
telemt_desync_suppressed_total 3208
telemt_desync_frames_bucket_total{bucket="1_2"} 723
telemt_desync_frames_bucket_total{bucket="3_10"} 1684
telemt_desync_frames_bucket_total{bucket="gt_10"} 2233
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 13735
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 13572
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 1094659
telemt_user_connections_current{user="hello"} 895
telemt_user_octets_from_client{user="hello"} 16457051824 (15.33 GB)
telemt_user_octets_to_client{user="hello"} 399363803161 (371.94 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 285
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 74382.1 (20h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 872978
telemt_connections_bad_total 11796
telemt_handshake_timeouts_total 65120
telemt_upstream_connect_attempt_total 19333
telemt_upstream_connect_success_total 19257
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 19333
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10833
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8411
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 1625
telemt_me_reconnect_attempts_total 23252
telemt_me_reconnect_success_total 15529
telemt_me_reader_eof_total 16585
telemt_me_idle_close_by_peer_total 16585
telemt_me_route_drop_no_conn_total 305912
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 754442
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1735
telemt_desync_full_logged_total 581
telemt_desync_suppressed_total 1154
telemt_desync_frames_bucket_total{bucket="1_2"} 487
telemt_desync_frames_bucket_total{bucket="3_10"} 674
telemt_desync_frames_bucket_total{bucket="gt_10"} 574
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 15894
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 15508
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 365
telemt_user_connections_total{user="hello"} 753856
telemt_user_connections_current{user="hello"} 611
telemt_user_octets_from_client{user="hello"} 9225120896 (8.59 GB)
telemt_user_octets_to_client{user="hello"} 305582914476 (284.60 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 74382.0 (20h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 978457
telemt_connections_bad_total 11415
telemt_handshake_timeouts_total 8087
telemt_upstream_connect_attempt_total 23476
telemt_upstream_connect_success_total 23197
telemt_upstream_connect_fail_total 279
telemt_upstream_connect_attempts_per_request{bucket="1"} 23476
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11880
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11190
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 279
telemt_me_keepalive_timeout_total 1379
telemt_me_reconnect_attempts_total 30485
telemt_me_reconnect_success_total 19451
telemt_me_reader_eof_total 20443
telemt_me_idle_close_by_peer_total 20443
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 363295
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 898327
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3466
telemt_desync_full_logged_total 1197
telemt_desync_suppressed_total 2269
telemt_desync_frames_bucket_total{bucket="1_2"} 972
telemt_desync_frames_bucket_total{bucket="3_10"} 1167
telemt_desync_frames_bucket_total{bucket="gt_10"} 1327
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 20014
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 19407
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 563
telemt_user_connections_total{user="hello"} 898205
telemt_user_connections_current{user="hello"} 788
telemt_user_octets_from_client{user="hello"} 11073514216 (10.31 GB)
telemt_user_octets_to_client{user="hello"} 292581382016 (272.49 GB)
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 138
```