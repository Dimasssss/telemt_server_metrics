# Server Metrics 2026-03-15 16:12:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 64687.8 (17h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2154737
telemt_connections_bad_total 126059
telemt_handshake_timeouts_total 26334
telemt_upstream_connect_attempt_total 12809
telemt_upstream_connect_success_total 12753
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 12809
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6626
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6074
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 14414
telemt_me_reconnect_success_total 9519
telemt_me_reader_eof_total 10175
telemt_me_idle_close_by_peer_total 10175
telemt_me_route_drop_no_conn_total 740612
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1813865
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6951
telemt_desync_full_logged_total 1916
telemt_desync_suppressed_total 5035
telemt_desync_frames_bucket_total{bucket="1_2"} 1707
telemt_desync_frames_bucket_total{bucket="3_10"} 2665
telemt_desync_frames_bucket_total{bucket="gt_10"} 2579
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 9829
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 9508
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 310
telemt_user_connections_total{user="hello"} 1813364
telemt_user_connections_current{user="hello"} 2476
telemt_user_octets_from_client{user="hello"} 26574513688 (24.75 GB)
telemt_user_octets_to_client{user="hello"} 695434501432 (647.67 GB)
telemt_user_unique_ips_current{user="hello"} 729
telemt_user_unique_ips_recent_window{user="hello"} 324
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 64688.7 (17h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 848233
telemt_connections_bad_total 45119
telemt_handshake_timeouts_total 59977
telemt_upstream_connect_attempt_total 16235
telemt_upstream_connect_success_total 16158
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 16235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8605
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7405
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 12681
telemt_me_reconnect_success_total 12578
telemt_me_reader_eof_total 13284
telemt_me_idle_close_by_peer_total 13284
telemt_me_route_drop_no_conn_total 215675
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 648333
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2097
telemt_desync_full_logged_total 706
telemt_desync_suppressed_total 1391
telemt_desync_frames_bucket_total{bucket="1_2"} 767
telemt_desync_frames_bucket_total{bucket="3_10"} 775
telemt_desync_frames_bucket_total{bucket="gt_10"} 555
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 12741
telemt_me_writer_restored_same_endpoint_total 12566
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 648576
telemt_user_connections_current{user="hello"} 823
telemt_user_octets_from_client{user="hello"} 9007132859 (8.39 GB)
telemt_user_octets_to_client{user="hello"} 246066319140 (229.17 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 64688.7 (17h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1927453
telemt_connections_bad_total 48232
telemt_handshake_timeouts_total 189454
telemt_upstream_connect_attempt_total 14014
telemt_upstream_connect_success_total 13948
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 14014
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6687
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 11953
telemt_me_reconnect_success_total 10688
telemt_me_reader_eof_total 11327
telemt_me_idle_close_by_peer_total 11327
telemt_me_route_drop_no_conn_total 495481
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1153666
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2856
telemt_desync_full_logged_total 1038
telemt_desync_suppressed_total 1818
telemt_desync_frames_bucket_total{bucket="1_2"} 665
telemt_desync_frames_bucket_total{bucket="3_10"} 1097
telemt_desync_frames_bucket_total{bucket="gt_10"} 1094
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 10876
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 10669
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 1149636
telemt_user_connections_current{user="hello"} 1547
telemt_user_octets_from_client{user="hello"} 16580968380 (15.44 GB)
telemt_user_octets_to_client{user="hello"} 412464452916 (384.14 GB)
telemt_user_unique_ips_current{user="hello"} 473
telemt_user_unique_ips_recent_window{user="hello"} 210
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 64688.6 (17h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 901390
telemt_connections_bad_total 78098
telemt_handshake_timeouts_total 43839
telemt_upstream_connect_attempt_total 168612
telemt_upstream_connect_success_total 168091
telemt_upstream_connect_fail_total 521
telemt_upstream_connect_attempts_per_request{bucket="1"} 168612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12772
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 521
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 53235
telemt_me_reconnect_success_total 12789
telemt_me_reader_eof_total 14407
telemt_me_idle_close_by_peer_total 14407
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 202124
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 541763
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1490
telemt_desync_full_logged_total 389
telemt_desync_suppressed_total 1101
telemt_desync_frames_bucket_total{bucket="1_2"} 385
telemt_desync_frames_bucket_total{bucket="3_10"} 598
telemt_desync_frames_bucket_total{bucket="gt_10"} 507
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 14182
telemt_me_refill_failed_total 1265
telemt_me_writer_restored_same_endpoint_total 12754
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1393
telemt_user_connections_total{user="hello"} 693414
telemt_user_connections_current{user="hello"} 913
telemt_user_octets_from_client{user="hello"} 13455753190 (12.53 GB)
telemt_user_octets_to_client{user="hello"} 245273467949 (228.43 GB)
telemt_user_msgs_from_client{user="hello"} 3034166
telemt_user_msgs_to_client{user="hello"} 10923814
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 64689.6 (17h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 908790
telemt_connections_bad_total 9976
telemt_handshake_timeouts_total 19869
telemt_upstream_connect_attempt_total 14488
telemt_upstream_connect_success_total 14408
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 14488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7744
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 14855
telemt_me_reconnect_success_total 11168
telemt_me_reader_eof_total 11900
telemt_me_idle_close_by_peer_total 11900
telemt_me_route_drop_no_conn_total 227160
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 750340
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2592
telemt_desync_full_logged_total 875
telemt_desync_suppressed_total 1717
telemt_desync_frames_bucket_total{bucket="1_2"} 795
telemt_desync_frames_bucket_total{bucket="3_10"} 983
telemt_desync_frames_bucket_total{bucket="gt_10"} 814
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 11418
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 11160
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 250
telemt_user_connections_total{user="hello"} 750382
telemt_user_connections_current{user="hello"} 931
telemt_user_octets_from_client{user="hello"} 9239911980 (8.61 GB)
telemt_user_octets_to_client{user="hello"} 269418142668 (250.92 GB)
telemt_user_unique_ips_current{user="hello"} 258
telemt_user_unique_ips_recent_window{user="hello"} 133
```