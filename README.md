# Server Metrics 2026-03-13 08:11:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 94355.5 (26h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2623579
telemt_connections_bad_total 36269
telemt_handshake_timeouts_total 28192
telemt_upstream_connect_attempt_total 18342
telemt_upstream_connect_success_total 18241
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 18342
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8760
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_timeout_total 1366
telemt_me_reconnect_attempts_total 22439
telemt_me_reconnect_success_total 13566
telemt_me_reader_eof_total 14622
telemt_me_idle_close_by_peer_total 14621
telemt_me_route_drop_no_conn_total 979346
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2400158
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10859
telemt_desync_full_logged_total 2802
telemt_desync_suppressed_total 8057
telemt_desync_frames_bucket_total{bucket="1_2"} 2780
telemt_desync_frames_bucket_total{bucket="3_10"} 4050
telemt_desync_frames_bucket_total{bucket="gt_10"} 4029
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 14032
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 13553
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 466
telemt_user_connections_total{user="hello"} 2399682
telemt_user_connections_current{user="hello"} 1643
telemt_user_octets_from_client{user="hello"} 34063208552 (31.72 GB)
telemt_user_octets_to_client{user="hello"} 801740893908 (746.68 GB)
telemt_user_unique_ips_current{user="hello"} 448
telemt_user_unique_ips_recent_window{user="hello"} 237
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 123975.9 (34h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1070314
telemt_connections_bad_total 13524
telemt_handshake_timeouts_total 83125
telemt_upstream_connect_attempt_total 30982
telemt_upstream_connect_success_total 30951
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 30982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15963
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14898
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3630
telemt_me_reconnect_attempts_total 23281
telemt_me_reconnect_success_total 23160
telemt_me_reader_eof_total 24685
telemt_me_idle_close_by_peer_total 24685
telemt_me_route_drop_no_conn_total 330167
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 933253
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4134
telemt_desync_full_logged_total 1263
telemt_desync_suppressed_total 2871
telemt_desync_frames_bucket_total{bucket="1_2"} 1534
telemt_desync_frames_bucket_total{bucket="3_10"} 1349
telemt_desync_frames_bucket_total{bucket="gt_10"} 1251
telemt_pool_swap_total 127
telemt_me_writer_removed_unexpected_total 23387
telemt_me_writer_restored_same_endpoint_total 23151
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 227
telemt_user_connections_total{user="hello"} 935178
telemt_user_connections_current{user="hello"} 554
telemt_user_octets_from_client{user="hello"} 14337200368 (13.35 GB)
telemt_user_octets_to_client{user="hello"} 348171751839 (324.26 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 123975.7 (34h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2104988
telemt_connections_bad_total 23664
telemt_handshake_timeouts_total 141542
telemt_upstream_connect_attempt_total 28476
telemt_upstream_connect_success_total 28466
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 28476
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14932
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13419
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1743
telemt_me_reconnect_attempts_total 23239
telemt_me_reconnect_success_total 21959
telemt_me_reader_eof_total 23256
telemt_me_idle_close_by_peer_total 23255
telemt_me_route_drop_no_conn_total 680107
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1673016
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5674
telemt_desync_full_logged_total 1796
telemt_desync_suppressed_total 3878
telemt_desync_frames_bucket_total{bucket="1_2"} 931
telemt_desync_frames_bucket_total{bucket="3_10"} 2072
telemt_desync_frames_bucket_total{bucket="gt_10"} 2671
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 22174
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 21918
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 215
telemt_user_connections_total{user="hello"} 1672480
telemt_user_connections_current{user="hello"} 957
telemt_user_octets_from_client{user="hello"} 27801666952 (25.89 GB)
telemt_user_octets_to_client{user="hello"} 608817932065 (567.01 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 282
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 123976.2 (34h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1323545
telemt_connections_bad_total 14216
telemt_handshake_timeouts_total 82643
telemt_upstream_connect_attempt_total 41550
telemt_upstream_connect_success_total 39249
telemt_upstream_connect_fail_total 2164
telemt_upstream_connect_attempts_per_request{bucket="1"} 41276
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23956
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15202
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2163
telemt_me_keepalive_timeout_total 11445
telemt_me_reconnect_attempts_total 36171
telemt_me_reconnect_success_total 27233
telemt_me_reader_eof_total 29330
telemt_me_idle_close_by_peer_total 29323
telemt_me_route_drop_no_conn_total 468507
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1112842
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2174
telemt_desync_full_logged_total 707
telemt_desync_suppressed_total 1467
telemt_desync_frames_bucket_total{bucket="1_2"} 595
telemt_desync_frames_bucket_total{bucket="3_10"} 837
telemt_desync_frames_bucket_total{bucket="gt_10"} 742
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 27702
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 27209
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 469
telemt_user_connections_total{user="hello"} 1117593
telemt_user_connections_current{user="hello"} 673
telemt_user_octets_from_client{user="hello"} 16914528397 (15.75 GB)
telemt_user_octets_to_client{user="hello"} 446403536878 (415.75 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 123976.0 (34h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1471581
telemt_connections_bad_total 28380
telemt_handshake_timeouts_total 12277
telemt_upstream_connect_attempt_total 39028
telemt_upstream_connect_success_total 38553
telemt_upstream_connect_fail_total 475
telemt_upstream_connect_attempts_per_request{bucket="1"} 39028
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19582
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18767
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 475
telemt_me_keepalive_timeout_total 2133
telemt_me_reconnect_attempts_total 46142
telemt_me_reconnect_success_total 32401
telemt_me_reader_eof_total 34007
telemt_me_idle_close_by_peer_total 34007
telemt_me_seq_mismatch_total 44
telemt_me_route_drop_no_conn_total 539277
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1350732
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 48
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4761
telemt_desync_full_logged_total 1699
telemt_desync_suppressed_total 3062
telemt_desync_frames_bucket_total{bucket="1_2"} 1448
telemt_desync_frames_bucket_total{bucket="3_10"} 1539
telemt_desync_frames_bucket_total{bucket="gt_10"} 1774
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 33187
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 32345
telemt_me_writer_restored_fallback_total 56
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 786
telemt_user_connections_total{user="hello"} 1350540
telemt_user_connections_current{user="hello"} 810
telemt_user_octets_from_client{user="hello"} 17206950236 (16.03 GB)
telemt_user_octets_to_client{user="hello"} 466041708936 (434.04 GB)
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 130
```