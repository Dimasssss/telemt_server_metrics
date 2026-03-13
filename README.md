# Server Metrics 2026-03-13 09:38:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 99561.3 (27h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2843984
telemt_connections_bad_total 36389
telemt_handshake_timeouts_total 41392
telemt_upstream_connect_attempt_total 19585
telemt_upstream_connect_success_total 19477
telemt_upstream_connect_fail_total 108
telemt_upstream_connect_attempts_per_request{bucket="1"} 19585
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10029
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9399
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 108
telemt_me_keepalive_timeout_total 1399
telemt_me_reconnect_attempts_total 24596
telemt_me_reconnect_success_total 14533
telemt_me_reader_eof_total 15661
telemt_me_idle_close_by_peer_total 15660
telemt_me_route_drop_no_conn_total 1055047
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2599868
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11373
telemt_desync_full_logged_total 2944
telemt_desync_suppressed_total 8429
telemt_desync_frames_bucket_total{bucket="1_2"} 2918
telemt_desync_frames_bucket_total{bucket="3_10"} 4257
telemt_desync_frames_bucket_total{bucket="gt_10"} 4198
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 15048
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 14520
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 515
telemt_user_connections_total{user="hello"} 2599591
telemt_user_connections_current{user="hello"} 1669
telemt_user_octets_from_client{user="hello"} 36177941512 (33.69 GB)
telemt_user_octets_to_client{user="hello"} 848747332584 (790.46 GB)
telemt_user_unique_ips_current{user="hello"} 451
telemt_user_unique_ips_recent_window{user="hello"} 252
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 129181.7 (35h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1159650
telemt_connections_bad_total 14496
telemt_handshake_timeouts_total 106510
telemt_upstream_connect_attempt_total 32038
telemt_upstream_connect_success_total 32007
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 32038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15418
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3690
telemt_me_reconnect_attempts_total 24074
telemt_me_reconnect_success_total 23948
telemt_me_reader_eof_total 25525
telemt_me_idle_close_by_peer_total 25525
telemt_me_route_drop_no_conn_total 356868
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 997020
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4395
telemt_desync_full_logged_total 1329
telemt_desync_suppressed_total 3066
telemt_desync_frames_bucket_total{bucket="1_2"} 1601
telemt_desync_frames_bucket_total{bucket="3_10"} 1449
telemt_desync_frames_bucket_total{bucket="gt_10"} 1345
telemt_pool_swap_total 133
telemt_me_writer_removed_unexpected_total 24182
telemt_me_writer_restored_same_endpoint_total 23939
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 998947
telemt_user_connections_current{user="hello"} 576
telemt_user_octets_from_client{user="hello"} 15238528412 (14.19 GB)
telemt_user_octets_to_client{user="hello"} 366324892135 (341.17 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 129181.7 (35h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2228585
telemt_connections_bad_total 24653
telemt_handshake_timeouts_total 150252
telemt_upstream_connect_attempt_total 29640
telemt_upstream_connect_success_total 29630
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 29640
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13984
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1815
telemt_me_reconnect_attempts_total 24138
telemt_me_reconnect_success_total 22851
telemt_me_reader_eof_total 24207
telemt_me_idle_close_by_peer_total 24206
telemt_me_route_drop_no_conn_total 726141
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1782955
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5898
telemt_desync_full_logged_total 1879
telemt_desync_suppressed_total 4019
telemt_desync_frames_bucket_total{bucket="1_2"} 965
telemt_desync_frames_bucket_total{bucket="3_10"} 2152
telemt_desync_frames_bucket_total{bucket="gt_10"} 2781
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 23079
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 22810
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 228
telemt_user_connections_total{user="hello"} 1782382
telemt_user_connections_current{user="hello"} 858
telemt_user_octets_from_client{user="hello"} 31084359812 (28.95 GB)
telemt_user_octets_to_client{user="hello"} 641910414697 (597.83 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 129182.0 (35h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1412510
telemt_connections_bad_total 14230
telemt_handshake_timeouts_total 86868
telemt_upstream_connect_attempt_total 42536
telemt_upstream_connect_success_total 40231
telemt_upstream_connect_fail_total 2168
telemt_upstream_connect_attempts_per_request{bucket="1"} 42262
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15640
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2167
telemt_me_keepalive_timeout_total 11470
telemt_me_reconnect_attempts_total 36892
telemt_me_reconnect_success_total 27949
telemt_me_reader_eof_total 30095
telemt_me_idle_close_by_peer_total 30088
telemt_me_route_drop_no_conn_total 497814
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1178825
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2220
telemt_desync_full_logged_total 729
telemt_desync_suppressed_total 1491
telemt_desync_frames_bucket_total{bucket="1_2"} 613
telemt_desync_frames_bucket_total{bucket="3_10"} 853
telemt_desync_frames_bucket_total{bucket="gt_10"} 754
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 28430
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 27925
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 481
telemt_user_connections_total{user="hello"} 1183587
telemt_user_connections_current{user="hello"} 619
telemt_user_octets_from_client{user="hello"} 17968203209 (16.73 GB)
telemt_user_octets_to_client{user="hello"} 470124742254 (437.84 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 129181.8 (35h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1575395
telemt_connections_bad_total 36062
telemt_handshake_timeouts_total 12849
telemt_upstream_connect_attempt_total 41400
telemt_upstream_connect_success_total 40907
telemt_upstream_connect_fail_total 493
telemt_upstream_connect_attempts_per_request{bucket="1"} 41400
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20096
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 195
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 493
telemt_me_keepalive_timeout_total 2214
telemt_me_reconnect_attempts_total 51075
telemt_me_reconnect_success_total 34476
telemt_me_reader_eof_total 36188
telemt_me_idle_close_by_peer_total 36188
telemt_me_seq_mismatch_total 48
telemt_me_route_drop_no_conn_total 576382
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1436329
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 52
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4996
telemt_desync_full_logged_total 1781
telemt_desync_suppressed_total 3215
telemt_desync_frames_bucket_total{bucket="1_2"} 1522
telemt_desync_frames_bucket_total{bucket="3_10"} 1616
telemt_desync_frames_bucket_total{bucket="gt_10"} 1858
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 35372
telemt_me_refill_failed_total 514
telemt_me_writer_restored_same_endpoint_total 34415
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 896
telemt_user_connections_total{user="hello"} 1436129
telemt_user_connections_current{user="hello"} 1002
telemt_user_octets_from_client{user="hello"} 18417104404 (17.15 GB)
telemt_user_octets_to_client{user="hello"} 495607672444 (461.57 GB)
telemt_user_unique_ips_current{user="hello"} 223
telemt_user_unique_ips_recent_window{user="hello"} 139
```