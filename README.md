# Server Metrics 2026-03-15 12:12:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 50280.7 (13h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1392036
telemt_connections_bad_total 82391
telemt_handshake_timeouts_total 11469
telemt_upstream_connect_attempt_total 10057
telemt_upstream_connect_success_total 10010
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 10057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4663
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 12376
telemt_me_reconnect_success_total 7501
telemt_me_reader_eof_total 8050
telemt_me_idle_close_by_peer_total 8050
telemt_me_route_drop_no_conn_total 463694
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1166576
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4420
telemt_desync_full_logged_total 1255
telemt_desync_suppressed_total 3165
telemt_desync_frames_bucket_total{bucket="1_2"} 1067
telemt_desync_frames_bucket_total{bucket="3_10"} 1738
telemt_desync_frames_bucket_total{bucket="gt_10"} 1615
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7765
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 7490
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 264
telemt_user_connections_total{user="hello"} 1166271
telemt_user_connections_current{user="hello"} 2317
telemt_user_octets_from_client{user="hello"} 16300100368 (15.18 GB)
telemt_user_octets_to_client{user="hello"} 468168131608 (436.02 GB)
telemt_user_unique_ips_current{user="hello"} 645
telemt_user_unique_ips_recent_window{user="hello"} 302
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 50281.4 (13h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 549334
telemt_connections_bad_total 28543
telemt_handshake_timeouts_total 30356
telemt_upstream_connect_attempt_total 13107
telemt_upstream_connect_success_total 13042
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 13107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7036
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5890
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 10274
telemt_me_reconnect_success_total 10201
telemt_me_reader_eof_total 10791
telemt_me_idle_close_by_peer_total 10791
telemt_me_route_drop_no_conn_total 140557
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 429962
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1674
telemt_desync_full_logged_total 577
telemt_desync_suppressed_total 1097
telemt_desync_frames_bucket_total{bucket="1_2"} 630
telemt_desync_frames_bucket_total{bucket="3_10"} 611
telemt_desync_frames_bucket_total{bucket="gt_10"} 433
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 10315
telemt_me_writer_restored_same_endpoint_total 10189
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 430230
telemt_user_connections_current{user="hello"} 739
telemt_user_octets_from_client{user="hello"} 6120768295 (5.70 GB)
telemt_user_octets_to_client{user="hello"} 160130040412 (149.13 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 242
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 50281.4 (13h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1095840
telemt_connections_bad_total 35986
telemt_handshake_timeouts_total 110246
telemt_upstream_connect_attempt_total 11083
telemt_upstream_connect_success_total 11030
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 11083
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5698
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5275
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_reconnect_attempts_total 9751
telemt_me_reconnect_success_total 8509
telemt_me_reader_eof_total 9030
telemt_me_idle_close_by_peer_total 9030
telemt_me_route_drop_no_conn_total 319552
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 746750
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1927
telemt_desync_full_logged_total 673
telemt_desync_suppressed_total 1254
telemt_desync_frames_bucket_total{bucket="1_2"} 428
telemt_desync_frames_bucket_total{bucket="3_10"} 720
telemt_desync_frames_bucket_total{bucket="gt_10"} 779
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 8657
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 8490
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 148
telemt_user_connections_total{user="hello"} 744230
telemt_user_connections_current{user="hello"} 1213
telemt_user_octets_from_client{user="hello"} 10897046232 (10.15 GB)
telemt_user_octets_to_client{user="hello"} 282326326948 (262.94 GB)
telemt_user_unique_ips_current{user="hello"} 390
telemt_user_unique_ips_recent_window{user="hello"} 197
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 50281.4 (13h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 554767
telemt_connections_bad_total 65205
telemt_handshake_timeouts_total 32557
telemt_upstream_connect_attempt_total 14507
telemt_upstream_connect_success_total 14130
telemt_upstream_connect_fail_total 377
telemt_upstream_connect_attempts_per_request{bucket="1"} 14507
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6696
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7431
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 377
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 38339
telemt_me_reconnect_success_total 11621
telemt_me_reader_eof_total 12790
telemt_me_idle_close_by_peer_total 12790
telemt_me_seq_mismatch_total 18
telemt_me_route_drop_no_conn_total 156760
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 413687
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1097
telemt_desync_full_logged_total 281
telemt_desync_suppressed_total 816
telemt_desync_frames_bucket_total{bucket="1_2"} 292
telemt_desync_frames_bucket_total{bucket="3_10"} 453
telemt_desync_frames_bucket_total{bucket="gt_10"} 352
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 12566
telemt_me_refill_failed_total 835
telemt_me_writer_restored_same_endpoint_total 11589
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 945
telemt_user_connections_total{user="hello"} 413581
telemt_user_connections_current{user="hello"} 644
telemt_user_octets_from_client{user="hello"} 6185505388 (5.76 GB)
telemt_user_octets_to_client{user="hello"} 138421435492 (128.92 GB)
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 50282.0 (13h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 589663
telemt_connections_bad_total 6582
telemt_handshake_timeouts_total 12903
telemt_upstream_connect_attempt_total 11154
telemt_upstream_connect_success_total 11097
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 11154
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5093
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5999
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_reconnect_attempts_total 8640
telemt_me_reconnect_success_total 8593
telemt_me_reader_eof_total 9120
telemt_me_idle_close_by_peer_total 9120
telemt_me_route_drop_no_conn_total 149286
telemt_me_route_drop_channel_closed_total 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 482300
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1902
telemt_desync_full_logged_total 624
telemt_desync_suppressed_total 1278
telemt_desync_frames_bucket_total{bucket="1_2"} 547
telemt_desync_frames_bucket_total{bucket="3_10"} 762
telemt_desync_frames_bucket_total{bucket="gt_10"} 593
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 8691
telemt_me_writer_restored_same_endpoint_total 8585
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 482334
telemt_user_connections_current{user="hello"} 849
telemt_user_octets_from_client{user="hello"} 6268757900 (5.84 GB)
telemt_user_octets_to_client{user="hello"} 174120410392 (162.16 GB)
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 102
```