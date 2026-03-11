# Server Metrics 2026-03-11 20:23:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 107772.8 (29h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2737126
telemt_connections_bad_total 55120
telemt_handshake_timeouts_total 62160
telemt_upstream_connect_attempt_total 22764
telemt_upstream_connect_success_total 22752
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 22764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11474
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11166
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5403
telemt_me_reconnect_attempts_total 35194
telemt_me_reconnect_success_total 17300
telemt_me_reader_eof_total 18690
telemt_me_idle_close_by_peer_total 18690
telemt_me_route_drop_no_conn_total 1030322
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2491725
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12633
telemt_desync_full_logged_total 3510
telemt_desync_suppressed_total 9123
telemt_desync_frames_bucket_total{bucket="1_2"} 3116
telemt_desync_frames_bucket_total{bucket="3_10"} 4859
telemt_desync_frames_bucket_total{bucket="gt_10"} 4658
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 18059
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 17294
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 759
telemt_user_connections_total{user="hello"} 2490076
telemt_user_connections_current{user="hello"} 1072
telemt_user_octets_from_client{user="hello"} 37540376016 (34.96 GB)
telemt_user_octets_to_client{user="hello"} 713979019220 (664.94 GB)
telemt_user_unique_ips_current{user="hello"} 309
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 107829.5 (29h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1007108
telemt_connections_bad_total 16558
telemt_handshake_timeouts_total 90378
telemt_upstream_connect_attempt_total 33009
telemt_upstream_connect_success_total 30037
telemt_upstream_connect_fail_total 2972
telemt_upstream_connect_attempts_per_request{bucket="1"} 33009
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13518
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2088
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2972
telemt_me_keepalive_timeout_total 2881
telemt_me_reconnect_attempts_total 23795
telemt_me_reconnect_success_total 21671
telemt_me_reader_eof_total 22954
telemt_me_idle_close_by_peer_total 22951
telemt_me_route_drop_no_conn_total 380987
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 841003
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3339
telemt_desync_full_logged_total 1084
telemt_desync_suppressed_total 2255
telemt_desync_frames_bucket_total{bucket="1_2"} 1074
telemt_desync_frames_bucket_total{bucket="3_10"} 1182
telemt_desync_frames_bucket_total{bucket="gt_10"} 1083
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 21990
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 21648
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 319
telemt_user_connections_total{user="hello"} 843445
telemt_user_connections_current{user="hello"} 347
telemt_user_octets_from_client{user="hello"} 10182589050 (9.48 GB)
telemt_user_octets_to_client{user="hello"} 247287389824 (230.30 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 107829.6 (29h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1748402
telemt_connections_bad_total 11106
telemt_handshake_timeouts_total 135111
telemt_upstream_connect_attempt_total 27388
telemt_upstream_connect_success_total 27042
telemt_upstream_connect_fail_total 346
telemt_upstream_connect_attempts_per_request{bucket="1"} 27388
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14654
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12250
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 346
telemt_me_keepalive_timeout_total 2012
telemt_me_reconnect_attempts_total 56896
telemt_me_reconnect_success_total 20520
telemt_me_reader_eof_total 22517
telemt_me_idle_close_by_peer_total 22517
telemt_me_route_drop_no_conn_total 636353
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1536972
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4169
telemt_desync_full_logged_total 1228
telemt_desync_suppressed_total 2941
telemt_desync_frames_bucket_total{bucket="1_2"} 970
telemt_desync_frames_bucket_total{bucket="3_10"} 1584
telemt_desync_frames_bucket_total{bucket="gt_10"} 1615
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 21939
telemt_me_refill_failed_total 1131
telemt_me_writer_restored_same_endpoint_total 20508
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1419
telemt_user_connections_total{user="hello"} 1536606
telemt_user_connections_current{user="hello"} 568
telemt_user_octets_from_client{user="hello"} 19786181505 (18.43 GB)
telemt_user_octets_to_client{user="hello"} 471192585449 (438.83 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 107829.9 (29h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1249448
telemt_connections_bad_total 78228
telemt_handshake_timeouts_total 111386
telemt_upstream_connect_attempt_total 28983
telemt_upstream_connect_success_total 28983
telemt_upstream_connect_attempts_per_request{bucket="1"} 28983
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13193
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1491
telemt_me_reconnect_attempts_total 28214
telemt_me_reconnect_success_total 23595
telemt_me_reader_eof_total 25059
telemt_me_idle_close_by_peer_total 25058
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 419381
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1024208
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2191
telemt_desync_full_logged_total 824
telemt_desync_suppressed_total 1367
telemt_desync_frames_bucket_total{bucket="1_2"} 778
telemt_desync_frames_bucket_total{bucket="3_10"} 736
telemt_desync_frames_bucket_total{bucket="gt_10"} 677
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 23988
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 23562
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 393
telemt_user_connections_total{user="hello"} 1023334
telemt_user_connections_current{user="hello"} 353
telemt_user_octets_from_client{user="hello"} 12159419912 (11.32 GB)
telemt_user_octets_to_client{user="hello"} 312145533380 (290.71 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 12505.9 (3h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 187937
telemt_connections_bad_total 5148
telemt_handshake_timeouts_total 2101
telemt_upstream_connect_attempt_total 3562
telemt_upstream_connect_success_total 3561
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3562
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1701
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 2917
telemt_me_reconnect_success_total 2888
telemt_me_reader_eof_total 2983
telemt_me_idle_close_by_peer_total 2983
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 63583
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165072
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 409
telemt_desync_full_logged_total 138
telemt_desync_suppressed_total 271
telemt_desync_frames_bucket_total{bucket="1_2"} 96
telemt_desync_frames_bucket_total{bucket="3_10"} 149
telemt_desync_frames_bucket_total{bucket="gt_10"} 164
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2923
telemt_me_writer_restored_same_endpoint_total 2863
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 165038
telemt_user_connections_current{user="hello"} 494
telemt_user_octets_from_client{user="hello"} 9490083832 (8.84 GB)
telemt_user_octets_to_client{user="hello"} 54963549360 (51.19 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 69
```