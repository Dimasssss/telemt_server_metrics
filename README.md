# Server Metrics 2026-03-13 05:27:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 84555.8 (23h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2275849
telemt_connections_bad_total 33468
telemt_handshake_timeouts_total 23947
telemt_upstream_connect_attempt_total 16613
telemt_upstream_connect_success_total 16521
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 16613
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8530
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7945
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 1309
telemt_me_reconnect_attempts_total 21196
telemt_me_reconnect_success_total 12329
telemt_me_reader_eof_total 13301
telemt_me_idle_close_by_peer_total 13300
telemt_me_route_drop_no_conn_total 866172
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2093127
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9248
telemt_desync_full_logged_total 2384
telemt_desync_suppressed_total 6864
telemt_desync_frames_bucket_total{bucket="1_2"} 2417
telemt_desync_frames_bucket_total{bucket="3_10"} 3363
telemt_desync_frames_bucket_total{bucket="gt_10"} 3468
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 12777
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 12316
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 448
telemt_user_connections_total{user="hello"} 2092505
telemt_user_connections_current{user="hello"} 1154
telemt_user_octets_from_client{user="hello"} 30325057828 (28.24 GB)
telemt_user_octets_to_client{user="hello"} 719615459780 (670.19 GB)
telemt_user_unique_ips_current{user="hello"} 328
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 114176.2 (31h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 923220
telemt_connections_bad_total 12375
telemt_handshake_timeouts_total 40316
telemt_upstream_connect_attempt_total 28870
telemt_upstream_connect_success_total 28839
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 28870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14903
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13846
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3539
telemt_me_reconnect_attempts_total 21647
telemt_me_reconnect_success_total 21530
telemt_me_reader_eof_total 22953
telemt_me_idle_close_by_peer_total 22953
telemt_me_route_drop_no_conn_total 294128
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 832314
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3310
telemt_desync_full_logged_total 1042
telemt_desync_suppressed_total 2268
telemt_desync_frames_bucket_total{bucket="1_2"} 1310
telemt_desync_frames_bucket_total{bucket="3_10"} 1081
telemt_desync_frames_bucket_total{bucket="gt_10"} 919
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 21743
telemt_me_writer_restored_same_endpoint_total 21521
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 213
telemt_user_connections_total{user="hello"} 834208
telemt_user_connections_current{user="hello"} 424
telemt_user_octets_from_client{user="hello"} 13296852644 (12.38 GB)
telemt_user_octets_to_client{user="hello"} 318683151291 (296.80 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 114176.2 (31h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1906266
telemt_connections_bad_total 20176
telemt_handshake_timeouts_total 125268
telemt_upstream_connect_attempt_total 26550
telemt_upstream_connect_success_total 26540
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 26550
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13918
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12515
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1646
telemt_me_reconnect_attempts_total 21792
telemt_me_reconnect_success_total 20521
telemt_me_reader_eof_total 21735
telemt_me_idle_close_by_peer_total 21734
telemt_me_route_drop_no_conn_total 612496
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1502316
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5229
telemt_desync_full_logged_total 1593
telemt_desync_suppressed_total 3636
telemt_desync_frames_bucket_total{bucket="1_2"} 856
telemt_desync_frames_bucket_total{bucket="3_10"} 1893
telemt_desync_frames_bucket_total{bucket="gt_10"} 2480
telemt_pool_swap_total 107
telemt_me_writer_removed_unexpected_total 20718
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 20480
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 197
telemt_user_connections_total{user="hello"} 1501813
telemt_user_connections_current{user="hello"} 693
telemt_user_octets_from_client{user="hello"} 25812525068 (24.04 GB)
telemt_user_octets_to_client{user="hello"} 534765031249 (498.04 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 114176.5 (31h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1169864
telemt_connections_bad_total 13982
telemt_handshake_timeouts_total 75835
telemt_upstream_connect_attempt_total 38980
telemt_upstream_connect_success_total 36695
telemt_upstream_connect_fail_total 2148
telemt_upstream_connect_attempts_per_request{bucket="1"} 38706
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22601
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14003
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2147
telemt_me_keepalive_timeout_total 11398
telemt_me_reconnect_attempts_total 34096
telemt_me_reconnect_success_total 25162
telemt_me_reader_eof_total 27149
telemt_me_idle_close_by_peer_total 27142
telemt_me_route_drop_no_conn_total 416551
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1007247
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1982
telemt_desync_full_logged_total 652
telemt_desync_suppressed_total 1330
telemt_desync_frames_bucket_total{bucket="1_2"} 550
telemt_desync_frames_bucket_total{bucket="3_10"} 770
telemt_desync_frames_bucket_total{bucket="gt_10"} 662
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 25612
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 25138
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 450
telemt_user_connections_total{user="hello"} 1012429
telemt_user_connections_current{user="hello"} 435
telemt_user_octets_from_client{user="hello"} 15418203301 (14.36 GB)
telemt_user_octets_to_client{user="hello"} 401614876214 (374.03 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 114176.2 (31h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1309166
telemt_connections_bad_total 13055
telemt_handshake_timeouts_total 10742
telemt_upstream_connect_attempt_total 36050
telemt_upstream_connect_success_total 35616
telemt_upstream_connect_fail_total 434
telemt_upstream_connect_attempts_per_request{bucket="1"} 36050
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17268
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 177
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 434
telemt_me_keepalive_timeout_total 1962
telemt_me_reconnect_attempts_total 43683
telemt_me_reconnect_success_total 29950
telemt_me_reader_eof_total 31478
telemt_me_idle_close_by_peer_total 31478
telemt_me_seq_mismatch_total 39
telemt_me_route_drop_no_conn_total 484221
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1212060
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 43
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4380
telemt_desync_full_logged_total 1576
telemt_desync_suppressed_total 2804
telemt_desync_frames_bucket_total{bucket="1_2"} 1330
telemt_desync_frames_bucket_total{bucket="3_10"} 1422
telemt_desync_frames_bucket_total{bucket="gt_10"} 1628
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 30713
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 29899
telemt_me_writer_restored_fallback_total 51
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 763
telemt_user_connections_total{user="hello"} 1211917
telemt_user_connections_current{user="hello"} 560
telemt_user_octets_from_client{user="hello"} 14674794748 (13.67 GB)
telemt_user_octets_to_client{user="hello"} 411338372988 (383.09 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 72
```