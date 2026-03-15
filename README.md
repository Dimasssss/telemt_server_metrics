# Server Metrics 2026-03-15 02:31:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 15394.2 (4h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 187412
telemt_connections_bad_total 2445
telemt_handshake_timeouts_total 586
telemt_upstream_connect_attempt_total 3270
telemt_upstream_connect_success_total 3260
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 3270
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1693
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1564
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 2468
telemt_me_reconnect_success_total 2455
telemt_me_reader_eof_total 2587
telemt_me_idle_close_by_peer_total 2587
telemt_me_route_drop_no_conn_total 57957
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165210
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 450
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 327
telemt_desync_frames_bucket_total{bucket="1_2"} 103
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 170
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2484
telemt_me_writer_restored_same_endpoint_total 2444
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 165197
telemt_user_connections_current{user="hello"} 698
telemt_user_octets_from_client{user="hello"} 1808707816 (1.68 GB)
telemt_user_octets_to_client{user="hello"} 55553615024 (51.74 GB)
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 15394.6 (4h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77936
telemt_connections_bad_total 13830
telemt_handshake_timeouts_total 3611
telemt_upstream_connect_attempt_total 4559
telemt_upstream_connect_success_total 4538
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 4559
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2473
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2033
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 3442
telemt_me_reconnect_success_total 3422
telemt_me_reader_eof_total 3575
telemt_me_idle_close_by_peer_total 3575
telemt_me_route_drop_no_conn_total 15012
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 58489
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 108
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 83
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3401
telemt_me_writer_restored_same_endpoint_total 3414
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 58785
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 1553839903 (1.45 GB)
telemt_user_octets_to_client{user="hello"} 16456105324 (15.33 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 15394.9 (4h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128911
telemt_connections_bad_total 2363
telemt_handshake_timeouts_total 12104
telemt_upstream_connect_attempt_total 3604
telemt_upstream_connect_success_total 3587
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 3604
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1669
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_reconnect_attempts_total 2792
telemt_me_reconnect_success_total 2781
telemt_me_reader_eof_total 2930
telemt_me_idle_close_by_peer_total 2930
telemt_me_route_drop_no_conn_total 27597
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111859
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 250
telemt_desync_full_logged_total 131
telemt_desync_suppressed_total 119
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 106
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2810
telemt_me_writer_restored_same_endpoint_total 2762
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 111770
telemt_user_connections_current{user="hello"} 340
telemt_user_octets_from_client{user="hello"} 1058453456 (1009.42 MB)
telemt_user_octets_to_client{user="hello"} 36681219024 (34.16 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 15394.8 (4h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107839
telemt_connections_bad_total 27824
telemt_handshake_timeouts_total 2638
telemt_upstream_connect_attempt_total 5731
telemt_upstream_connect_success_total 5609
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 5731
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2678
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2929
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 8351
telemt_me_reconnect_success_total 4802
telemt_me_reader_eof_total 5043
telemt_me_idle_close_by_peer_total 5043
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 20599
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75708
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 124
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 93
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 4953
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 4783
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 151
telemt_user_connections_total{user="hello"} 75715
telemt_user_connections_current{user="hello"} 218
telemt_user_octets_from_client{user="hello"} 445242744 (424.62 MB)
telemt_user_octets_to_client{user="hello"} 17461817376 (16.26 GB)
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 15395.4 (4h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64593
telemt_connections_bad_total 119
telemt_handshake_timeouts_total 726
telemt_upstream_connect_attempt_total 3512
telemt_upstream_connect_success_total 3496
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3512
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1446
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2046
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 2696
telemt_me_reconnect_success_total 2686
telemt_me_reader_eof_total 2841
telemt_me_idle_close_by_peer_total 2841
telemt_me_route_drop_no_conn_total 16154
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61963
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 217
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 157
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 89
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2706
telemt_me_writer_restored_same_endpoint_total 2678
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 61962
telemt_user_connections_current{user="hello"} 255
telemt_user_octets_from_client{user="hello"} 546061588 (520.76 MB)
telemt_user_octets_to_client{user="hello"} 20698149324 (19.28 GB)
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 26
```