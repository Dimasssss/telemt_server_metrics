# Server Metrics 2026-03-15 11:11:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 46602.9 (12h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1196153
telemt_connections_bad_total 76802
telemt_handshake_timeouts_total 9896
telemt_upstream_connect_attempt_total 9301
telemt_upstream_connect_success_total 9262
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 9301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4321
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 9440
telemt_me_reconnect_success_total 6934
telemt_me_reader_eof_total 7398
telemt_me_idle_close_by_peer_total 7398
telemt_me_route_drop_no_conn_total 398374
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1007464
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3859
telemt_desync_full_logged_total 1086
telemt_desync_suppressed_total 2773
telemt_desync_frames_bucket_total{bucket="1_2"} 938
telemt_desync_frames_bucket_total{bucket="3_10"} 1523
telemt_desync_frames_bucket_total{bucket="gt_10"} 1398
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7112
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 6923
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 1007467
telemt_user_connections_current{user="hello"} 2250
telemt_user_octets_from_client{user="hello"} 14214027304 (13.24 GB)
telemt_user_octets_to_client{user="hello"} 403750038444 (376.02 GB)
telemt_user_unique_ips_current{user="hello"} 615
telemt_user_unique_ips_recent_window{user="hello"} 276
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 46603.6 (12h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 468760
telemt_connections_bad_total 25259
telemt_handshake_timeouts_total 20526
telemt_upstream_connect_attempt_total 12262
telemt_upstream_connect_success_total 12198
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 12262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5490
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 9609
telemt_me_reconnect_success_total 9547
telemt_me_reader_eof_total 10100
telemt_me_idle_close_by_peer_total 10100
telemt_me_route_drop_no_conn_total 119982
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 369901
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1291
telemt_desync_full_logged_total 460
telemt_desync_suppressed_total 831
telemt_desync_frames_bucket_total{bucket="1_2"} 468
telemt_desync_frames_bucket_total{bucket="3_10"} 462
telemt_desync_frames_bucket_total{bucket="gt_10"} 361
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 9647
telemt_me_writer_restored_same_endpoint_total 9535
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 370174
telemt_user_connections_current{user="hello"} 700
telemt_user_octets_from_client{user="hello"} 5408113187 (5.04 GB)
telemt_user_octets_to_client{user="hello"} 141454503936 (131.74 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 46603.6 (12h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 912211
telemt_connections_bad_total 30230
telemt_handshake_timeouts_total 88522
telemt_upstream_connect_attempt_total 10238
telemt_upstream_connect_success_total 10193
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 10238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4860
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_reconnect_attempts_total 7909
telemt_me_reconnect_success_total 7857
telemt_me_reader_eof_total 8321
telemt_me_idle_close_by_peer_total 8321
telemt_me_route_drop_no_conn_total 249158
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 648547
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1567
telemt_desync_full_logged_total 553
telemt_desync_suppressed_total 1014
telemt_desync_frames_bucket_total{bucket="1_2"} 345
telemt_desync_frames_bucket_total{bucket="3_10"} 570
telemt_desync_frames_bucket_total{bucket="gt_10"} 652
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 7961
telemt_me_writer_restored_same_endpoint_total 7838
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 647720
telemt_user_connections_current{user="hello"} 1220
telemt_user_octets_from_client{user="hello"} 9767381064 (9.10 GB)
telemt_user_octets_to_client{user="hello"} 255869225128 (238.30 GB)
telemt_user_unique_ips_current{user="hello"} 354
telemt_user_unique_ips_recent_window{user="hello"} 183
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 46603.7 (12h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 481337
telemt_connections_bad_total 59294
telemt_handshake_timeouts_total 26460
telemt_upstream_connect_attempt_total 13932
telemt_upstream_connect_success_total 13579
telemt_upstream_connect_fail_total 353
telemt_upstream_connect_attempts_per_request{bucket="1"} 13932
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6490
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7086
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 353
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 32699
telemt_me_reconnect_success_total 11246
telemt_me_reader_eof_total 12246
telemt_me_idle_close_by_peer_total 12246
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 135466
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 361360
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 844
telemt_desync_full_logged_total 215
telemt_desync_suppressed_total 629
telemt_desync_frames_bucket_total{bucket="1_2"} 212
telemt_desync_frames_bucket_total{bucket="3_10"} 334
telemt_desync_frames_bucket_total{bucket="gt_10"} 298
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 12019
telemt_me_refill_failed_total 670
telemt_me_writer_restored_same_endpoint_total 11214
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 773
telemt_user_connections_total{user="hello"} 361263
telemt_user_connections_current{user="hello"} 560
telemt_user_octets_from_client{user="hello"} 4438969512 (4.13 GB)
telemt_user_octets_to_client{user="hello"} 112310539556 (104.60 GB)
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 46604.4 (12h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 500486
telemt_connections_bad_total 6229
telemt_handshake_timeouts_total 10042
telemt_upstream_connect_attempt_total 10391
telemt_upstream_connect_success_total 10340
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 10391
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4712
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5623
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_reconnect_attempts_total 8060
telemt_me_reconnect_success_total 8018
telemt_me_reader_eof_total 8507
telemt_me_idle_close_by_peer_total 8507
telemt_me_route_drop_no_conn_total 129338
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 412666
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1603
telemt_desync_full_logged_total 522
telemt_desync_suppressed_total 1081
telemt_desync_frames_bucket_total{bucket="1_2"} 460
telemt_desync_frames_bucket_total{bucket="3_10"} 653
telemt_desync_frames_bucket_total{bucket="gt_10"} 490
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 8110
telemt_me_writer_restored_same_endpoint_total 8010
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 412688
telemt_user_connections_current{user="hello"} 837
telemt_user_octets_from_client{user="hello"} 5281856132 (4.92 GB)
telemt_user_octets_to_client{user="hello"} 154561313524 (143.95 GB)
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 106
```