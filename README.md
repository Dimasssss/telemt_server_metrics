# Server Metrics 2026-03-15 15:52:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 63461.1 (17h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2079815
telemt_connections_bad_total 113478
telemt_handshake_timeouts_total 24874
telemt_upstream_connect_attempt_total 12675
telemt_upstream_connect_success_total 12619
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 12675
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6566
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6001
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 14324
telemt_me_reconnect_success_total 9429
telemt_me_reader_eof_total 10078
telemt_me_idle_close_by_peer_total 10078
telemt_me_route_drop_no_conn_total 715662
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1756921
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6739
telemt_desync_full_logged_total 1857
telemt_desync_suppressed_total 4882
telemt_desync_frames_bucket_total{bucket="1_2"} 1662
telemt_desync_frames_bucket_total{bucket="3_10"} 2587
telemt_desync_frames_bucket_total{bucket="gt_10"} 2490
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 9735
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 9418
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 306
telemt_user_connections_total{user="hello"} 1756431
telemt_user_connections_current{user="hello"} 2367
telemt_user_octets_from_client{user="hello"} 25788223580 (24.02 GB)
telemt_user_octets_to_client{user="hello"} 674326072732 (628.02 GB)
telemt_user_unique_ips_current{user="hello"} 684
telemt_user_unique_ips_recent_window{user="hello"} 300
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 63462.0 (17h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 825721
telemt_connections_bad_total 44038
telemt_handshake_timeouts_total 59584
telemt_upstream_connect_attempt_total 15968
telemt_upstream_connect_success_total 15892
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 15968
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8471
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7275
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 12461
telemt_me_reconnect_success_total 12362
telemt_me_reader_eof_total 13062
telemt_me_idle_close_by_peer_total 13062
telemt_me_route_drop_no_conn_total 208480
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 629135
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2079
telemt_desync_full_logged_total 700
telemt_desync_suppressed_total 1379
telemt_desync_frames_bucket_total{bucket="1_2"} 765
telemt_desync_frames_bucket_total{bucket="3_10"} 763
telemt_desync_frames_bucket_total{bucket="gt_10"} 551
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 12520
telemt_me_writer_restored_same_endpoint_total 12350
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 629376
telemt_user_connections_current{user="hello"} 792
telemt_user_octets_from_client{user="hello"} 8789747307 (8.19 GB)
telemt_user_octets_to_client{user="hello"} 237465771176 (221.16 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 63462.0 (17h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1855094
telemt_connections_bad_total 47977
telemt_handshake_timeouts_total 184379
telemt_upstream_connect_attempt_total 13841
telemt_upstream_connect_success_total 13776
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 13841
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7099
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6610
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 11825
telemt_me_reconnect_success_total 10562
telemt_me_reader_eof_total 11195
telemt_me_idle_close_by_peer_total 11195
telemt_me_route_drop_no_conn_total 482134
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1117162
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2729
telemt_desync_full_logged_total 1004
telemt_desync_suppressed_total 1725
telemt_desync_frames_bucket_total{bucket="1_2"} 636
telemt_desync_frames_bucket_total{bucket="3_10"} 1056
telemt_desync_frames_bucket_total{bucket="gt_10"} 1037
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 10749
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 10543
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 1113128
telemt_user_connections_current{user="hello"} 1338
telemt_user_octets_from_client{user="hello"} 16006631780 (14.91 GB)
telemt_user_octets_to_client{user="hello"} 396249453584 (369.04 GB)
telemt_user_unique_ips_current{user="hello"} 417
telemt_user_unique_ips_recent_window{user="hello"} 201
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 63461.9 (17h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 875076
telemt_connections_bad_total 76967
telemt_handshake_timeouts_total 42903
telemt_upstream_connect_attempt_total 168281
telemt_upstream_connect_success_total 167765
telemt_upstream_connect_fail_total 516
telemt_upstream_connect_attempts_per_request{bucket="1"} 168281
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12607
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 516
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 52952
telemt_me_reconnect_success_total 12508
telemt_me_reader_eof_total 14123
telemt_me_idle_close_by_peer_total 14123
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 194702
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 520089
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1433
telemt_desync_full_logged_total 372
telemt_desync_suppressed_total 1061
telemt_desync_frames_bucket_total{bucket="1_2"} 374
telemt_desync_frames_bucket_total{bucket="3_10"} 578
telemt_desync_frames_bucket_total{bucket="gt_10"} 481
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 13897
telemt_me_refill_failed_total 1265
telemt_me_writer_restored_same_endpoint_total 12473
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1389
telemt_user_connections_total{user="hello"} 671740
telemt_user_connections_current{user="hello"} 922
telemt_user_octets_from_client{user="hello"} 13211942658 (12.30 GB)
telemt_user_octets_to_client{user="hello"} 237138293157 (220.85 GB)
telemt_user_msgs_from_client{user="hello"} 3034166
telemt_user_msgs_to_client{user="hello"} 10923814
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 63463.1 (17h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 882305
telemt_connections_bad_total 9435
telemt_handshake_timeouts_total 19551
telemt_upstream_connect_attempt_total 14140
telemt_upstream_connect_success_total 14061
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 14140
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6508
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7542
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 14552
telemt_me_reconnect_success_total 10869
telemt_me_reader_eof_total 11595
telemt_me_idle_close_by_peer_total 11595
telemt_me_route_drop_no_conn_total 219723
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 726747
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2505
telemt_desync_full_logged_total 853
telemt_desync_suppressed_total 1652
telemt_desync_frames_bucket_total{bucket="1_2"} 760
telemt_desync_frames_bucket_total{bucket="3_10"} 962
telemt_desync_frames_bucket_total{bucket="gt_10"} 783
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 11112
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 10861
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 726787
telemt_user_connections_current{user="hello"} 887
telemt_user_octets_from_client{user="hello"} 8898033268 (8.29 GB)
telemt_user_octets_to_client{user="hello"} 259919438720 (242.07 GB)
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 123
```