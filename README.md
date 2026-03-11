# Server Metrics 2026-03-11 21:09:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 110528.8 (30h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2796793
telemt_connections_bad_total 62981
telemt_handshake_timeouts_total 62576
telemt_upstream_connect_attempt_total 23581
telemt_upstream_connect_success_total 23569
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 23581
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11547
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5440
telemt_me_reconnect_attempts_total 35876
telemt_me_reconnect_success_total 17980
telemt_me_reader_eof_total 19399
telemt_me_idle_close_by_peer_total 19399
telemt_me_route_drop_no_conn_total 1049424
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2537706
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12707
telemt_desync_full_logged_total 3532
telemt_desync_suppressed_total 9175
telemt_desync_frames_bucket_total{bucket="1_2"} 3135
telemt_desync_frames_bucket_total{bucket="3_10"} 4881
telemt_desync_frames_bucket_total{bucket="gt_10"} 4691
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 18746
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 17974
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 766
telemt_user_connections_total{user="hello"} 2536039
telemt_user_connections_current{user="hello"} 784
telemt_user_octets_from_client{user="hello"} 38595113708 (35.94 GB)
telemt_user_octets_to_client{user="hello"} 731705823932 (681.45 GB)
telemt_user_unique_ips_current{user="hello"} 256
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 110585.4 (30h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1020798
telemt_connections_bad_total 17055
telemt_handshake_timeouts_total 90469
telemt_upstream_connect_attempt_total 33658
telemt_upstream_connect_success_total 30681
telemt_upstream_connect_fail_total 2977
telemt_upstream_connect_attempts_per_request{bucket="1"} 33658
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13863
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2091
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2977
telemt_me_keepalive_timeout_total 2912
telemt_me_reconnect_attempts_total 24310
telemt_me_reconnect_success_total 22180
telemt_me_reader_eof_total 23502
telemt_me_idle_close_by_peer_total 23499
telemt_me_route_drop_no_conn_total 386325
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 853582
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3377
telemt_desync_full_logged_total 1100
telemt_desync_suppressed_total 2277
telemt_desync_frames_bucket_total{bucket="1_2"} 1101
telemt_desync_frames_bucket_total{bucket="3_10"} 1193
telemt_desync_frames_bucket_total{bucket="gt_10"} 1083
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 22507
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 22157
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 327
telemt_user_connections_total{user="hello"} 856018
telemt_user_connections_current{user="hello"} 297
telemt_user_octets_from_client{user="hello"} 10328860678 (9.62 GB)
telemt_user_octets_to_client{user="hello"} 257153838496 (239.49 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 110585.3 (30h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1780436
telemt_connections_bad_total 11366
telemt_handshake_timeouts_total 136555
telemt_upstream_connect_attempt_total 34741
telemt_upstream_connect_success_total 34386
telemt_upstream_connect_fail_total 355
telemt_upstream_connect_attempts_per_request{bucket="1"} 34741
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21531
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12712
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 141
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 355
telemt_me_keepalive_timeout_total 2048
telemt_me_reconnect_attempts_total 61166
telemt_me_reconnect_success_total 20659
telemt_me_reader_eof_total 22784
telemt_me_idle_close_by_peer_total 22784
telemt_me_route_drop_no_conn_total 645137
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1559254
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4209
telemt_desync_full_logged_total 1242
telemt_desync_suppressed_total 2967
telemt_desync_frames_bucket_total{bucket="1_2"} 984
telemt_desync_frames_bucket_total{bucket="3_10"} 1601
telemt_desync_frames_bucket_total{bucket="gt_10"} 1624
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 22207
telemt_me_refill_failed_total 1260
telemt_me_writer_restored_same_endpoint_total 20647
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1548
telemt_user_connections_total{user="hello"} 1565942
telemt_user_connections_current{user="hello"} 457
telemt_user_octets_from_client{user="hello"} 19979416471 (18.61 GB)
telemt_user_octets_to_client{user="hello"} 479028133045 (446.13 GB)
telemt_user_msgs_from_client{user="hello"} 100707
telemt_user_msgs_to_client{user="hello"} 547991
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 110585.8 (30h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1274349
telemt_connections_bad_total 78277
telemt_handshake_timeouts_total 111698
telemt_upstream_connect_attempt_total 29663
telemt_upstream_connect_success_total 29663
telemt_upstream_connect_attempts_per_request{bucket="1"} 29663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16132
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13524
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1553
telemt_me_reconnect_attempts_total 28762
telemt_me_reconnect_success_total 24142
telemt_me_reader_eof_total 25638
telemt_me_idle_close_by_peer_total 25637
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 427945
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1048428
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2212
telemt_desync_full_logged_total 832
telemt_desync_suppressed_total 1380
telemt_desync_frames_bucket_total{bucket="1_2"} 781
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 688
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 24544
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 24109
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 402
telemt_user_connections_total{user="hello"} 1047549
telemt_user_connections_current{user="hello"} 294
telemt_user_octets_from_client{user="hello"} 12310520488 (11.47 GB)
telemt_user_octets_to_client{user="hello"} 316670914836 (294.92 GB)
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 15261.7 (4h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211987
telemt_connections_bad_total 5176
telemt_handshake_timeouts_total 2399
telemt_upstream_connect_attempt_total 4375
telemt_upstream_connect_success_total 4374
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4375
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2111
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 3596
telemt_me_reconnect_success_total 3562
telemt_me_reader_eof_total 3683
telemt_me_idle_close_by_peer_total 3683
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 72051
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 187449
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 475
telemt_desync_full_logged_total 164
telemt_desync_suppressed_total 311
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 169
telemt_desync_frames_bucket_total{bucket="gt_10"} 182
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3605
telemt_me_writer_restored_same_endpoint_total 3536
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 187411
telemt_user_connections_current{user="hello"} 417
telemt_user_octets_from_client{user="hello"} 9661910640 (9.00 GB)
telemt_user_octets_to_client{user="hello"} 65146386148 (60.67 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 43
```