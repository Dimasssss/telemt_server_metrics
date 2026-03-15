# Server Metrics 2026-03-15 15:57:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 63768.0 (17h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2100406
telemt_connections_bad_total 119237
telemt_handshake_timeouts_total 25285
telemt_upstream_connect_attempt_total 12689
telemt_upstream_connect_success_total 12633
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 12689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6571
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6010
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 14338
telemt_me_reconnect_success_total 9443
telemt_me_reader_eof_total 10094
telemt_me_idle_close_by_peer_total 10094
telemt_me_route_drop_no_conn_total 721236
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1770116
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6798
telemt_desync_full_logged_total 1874
telemt_desync_suppressed_total 4924
telemt_desync_frames_bucket_total{bucket="1_2"} 1681
telemt_desync_frames_bucket_total{bucket="3_10"} 2606
telemt_desync_frames_bucket_total{bucket="gt_10"} 2511
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 9751
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 9432
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 308
telemt_user_connections_total{user="hello"} 1769626
telemt_user_connections_current{user="hello"} 2350
telemt_user_octets_from_client{user="hello"} 25985816060 (24.20 GB)
telemt_user_octets_to_client{user="hello"} 678888517188 (632.26 GB)
telemt_user_unique_ips_current{user="hello"} 661
telemt_user_unique_ips_recent_window{user="hello"} 313
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 63768.7 (17h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 830695
telemt_connections_bad_total 44324
telemt_handshake_timeouts_total 59660
telemt_upstream_connect_attempt_total 16002
telemt_upstream_connect_success_total 15926
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 16002
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7297
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 12495
telemt_me_reconnect_success_total 12396
telemt_me_reader_eof_total 13096
telemt_me_idle_close_by_peer_total 13096
telemt_me_route_drop_no_conn_total 210109
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 633516
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2080
telemt_desync_full_logged_total 701
telemt_desync_suppressed_total 1379
telemt_desync_frames_bucket_total{bucket="1_2"} 765
telemt_desync_frames_bucket_total{bucket="3_10"} 763
telemt_desync_frames_bucket_total{bucket="gt_10"} 552
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 12554
telemt_me_writer_restored_same_endpoint_total 12384
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 633757
telemt_user_connections_current{user="hello"} 704
telemt_user_octets_from_client{user="hello"} 8849360955 (8.24 GB)
telemt_user_octets_to_client{user="hello"} 240936506000 (224.39 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 223
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 63768.5 (17h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1872395
telemt_connections_bad_total 48068
telemt_handshake_timeouts_total 185737
telemt_upstream_connect_attempt_total 13867
telemt_upstream_connect_success_total 13802
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 13867
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7117
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6618
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 11851
telemt_me_reconnect_success_total 10588
telemt_me_reader_eof_total 11221
telemt_me_idle_close_by_peer_total 11221
telemt_me_route_drop_no_conn_total 485375
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1125788
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2737
telemt_desync_full_logged_total 1007
telemt_desync_suppressed_total 1730
telemt_desync_frames_bucket_total{bucket="1_2"} 639
telemt_desync_frames_bucket_total{bucket="3_10"} 1056
telemt_desync_frames_bucket_total{bucket="gt_10"} 1042
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 10775
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 10569
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 1121752
telemt_user_connections_current{user="hello"} 1374
telemt_user_octets_from_client{user="hello"} 16140173164 (15.03 GB)
telemt_user_octets_to_client{user="hello"} 398848572156 (371.46 GB)
telemt_user_unique_ips_current{user="hello"} 406
telemt_user_unique_ips_recent_window{user="hello"} 203
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 63768.4 (17h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 881544
telemt_connections_bad_total 77256
telemt_handshake_timeouts_total 43073
telemt_upstream_connect_attempt_total 168324
telemt_upstream_connect_success_total 167808
telemt_upstream_connect_fail_total 516
telemt_upstream_connect_attempts_per_request{bucket="1"} 168324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12630
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 516
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 52995
telemt_me_reconnect_success_total 12551
telemt_me_reader_eof_total 14167
telemt_me_idle_close_by_peer_total 14167
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 196320
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 525426
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1441
telemt_desync_full_logged_total 376
telemt_desync_suppressed_total 1065
telemt_desync_frames_bucket_total{bucket="1_2"} 376
telemt_desync_frames_bucket_total{bucket="3_10"} 582
telemt_desync_frames_bucket_total{bucket="gt_10"} 483
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 13941
telemt_me_refill_failed_total 1265
telemt_me_writer_restored_same_endpoint_total 12516
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1390
telemt_user_connections_total{user="hello"} 677077
telemt_user_connections_current{user="hello"} 957
telemt_user_octets_from_client{user="hello"} 13321849306 (12.41 GB)
telemt_user_octets_to_client{user="hello"} 238519998497 (222.14 GB)
telemt_user_msgs_from_client{user="hello"} 3034166
telemt_user_msgs_to_client{user="hello"} 10923814
telemt_user_unique_ips_current{user="hello"} 251
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 63769.3 (17h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 888282
telemt_connections_bad_total 9444
telemt_handshake_timeouts_total 19703
telemt_upstream_connect_attempt_total 14192
telemt_upstream_connect_success_total 14113
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 14192
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6525
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7576
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 14604
telemt_me_reconnect_success_total 10921
telemt_me_reader_eof_total 11647
telemt_me_idle_close_by_peer_total 11647
telemt_me_route_drop_no_conn_total 221303
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 732111
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2527
telemt_desync_full_logged_total 859
telemt_desync_suppressed_total 1668
telemt_desync_frames_bucket_total{bucket="1_2"} 767
telemt_desync_frames_bucket_total{bucket="3_10"} 970
telemt_desync_frames_bucket_total{bucket="gt_10"} 790
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 11164
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 10913
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 732151
telemt_user_connections_current{user="hello"} 821
telemt_user_octets_from_client{user="hello"} 8978784800 (8.36 GB)
telemt_user_octets_to_client{user="hello"} 261735676512 (243.76 GB)
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 109
```