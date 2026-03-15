# Server Metrics 2026-03-15 09:29:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 40470.4 (11h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 896304
telemt_connections_bad_total 46362
telemt_handshake_timeouts_total 6578
telemt_upstream_connect_attempt_total 8128
telemt_upstream_connect_success_total 8093
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 8128
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4241
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3835
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6122
telemt_me_reconnect_success_total 6090
telemt_me_reader_eof_total 6441
telemt_me_idle_close_by_peer_total 6441
telemt_me_route_drop_no_conn_total 295019
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 756529
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2582
telemt_desync_full_logged_total 776
telemt_desync_suppressed_total 1806
telemt_desync_frames_bucket_total{bucket="1_2"} 604
telemt_desync_frames_bucket_total{bucket="3_10"} 974
telemt_desync_frames_bucket_total{bucket="gt_10"} 1004
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 6175
telemt_me_writer_restored_same_endpoint_total 6079
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 756513
telemt_user_connections_current{user="hello"} 1958
telemt_user_octets_from_client{user="hello"} 10899001556 (10.15 GB)
telemt_user_octets_to_client{user="hello"} 292801390148 (272.69 GB)
telemt_user_unique_ips_current{user="hello"} 550
telemt_user_unique_ips_recent_window{user="hello"} 283
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 40471.3 (11h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 354655
telemt_connections_bad_total 19547
telemt_handshake_timeouts_total 13741
telemt_upstream_connect_attempt_total 10714
telemt_upstream_connect_success_total 10660
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 10714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5791
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4781
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 8381
telemt_me_reconnect_success_total 8329
telemt_me_reader_eof_total 8826
telemt_me_idle_close_by_peer_total 8826
telemt_me_route_drop_no_conn_total 89967
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 280830
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1012
telemt_desync_full_logged_total 347
telemt_desync_suppressed_total 665
telemt_desync_frames_bucket_total{bucket="1_2"} 324
telemt_desync_frames_bucket_total{bucket="3_10"} 378
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 8399
telemt_me_writer_restored_same_endpoint_total 8321
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 281105
telemt_user_connections_current{user="hello"} 840
telemt_user_octets_from_client{user="hello"} 4079699443 (3.80 GB)
telemt_user_octets_to_client{user="hello"} 104669761020 (97.48 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 40471.3 (11h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 630325
telemt_connections_bad_total 21033
telemt_handshake_timeouts_total 62757
telemt_upstream_connect_attempt_total 9033
telemt_upstream_connect_success_total 8995
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 9033
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4243
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_reconnect_attempts_total 7020
telemt_me_reconnect_success_total 6974
telemt_me_reader_eof_total 7372
telemt_me_idle_close_by_peer_total 7372
telemt_me_route_drop_no_conn_total 185152
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 491604
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 982
telemt_desync_full_logged_total 377
telemt_desync_suppressed_total 605
telemt_desync_frames_bucket_total{bucket="1_2"} 211
telemt_desync_frames_bucket_total{bucket="3_10"} 356
telemt_desync_frames_bucket_total{bucket="gt_10"} 415
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7060
telemt_me_writer_restored_same_endpoint_total 6955
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 491120
telemt_user_connections_current{user="hello"} 1109
telemt_user_octets_from_client{user="hello"} 7468258680 (6.96 GB)
telemt_user_octets_to_client{user="hello"} 197354824096 (183.80 GB)
telemt_user_unique_ips_current{user="hello"} 323
telemt_user_unique_ips_recent_window{user="hello"} 201
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 40471.1 (11h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 376138
telemt_connections_bad_total 52466
telemt_handshake_timeouts_total 23985
telemt_upstream_connect_attempt_total 12696
telemt_upstream_connect_success_total 12394
telemt_upstream_connect_fail_total 302
telemt_upstream_connect_attempts_per_request{bucket="1"} 12696
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5789
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6602
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 302
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 26725
telemt_me_reconnect_success_total 10383
telemt_me_reader_eof_total 11205
telemt_me_idle_close_by_peer_total 11205
telemt_me_seq_mismatch_total 15
telemt_me_route_drop_no_conn_total 100898
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 280864
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 32
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 684
telemt_desync_full_logged_total 167
telemt_desync_suppressed_total 517
telemt_desync_frames_bucket_total{bucket="1_2"} 159
telemt_desync_frames_bucket_total{bucket="3_10"} 288
telemt_desync_frames_bucket_total{bucket="gt_10"} 237
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 10983
telemt_me_refill_failed_total 510
telemt_me_writer_restored_same_endpoint_total 10353
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 600
telemt_user_connections_total{user="hello"} 280874
telemt_user_connections_current{user="hello"} 597
telemt_user_octets_from_client{user="hello"} 2690502632 (2.51 GB)
telemt_user_octets_to_client{user="hello"} 89842480264 (83.67 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 40472.3 (11h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 349057
telemt_connections_bad_total 3836
telemt_handshake_timeouts_total 3741
telemt_upstream_connect_attempt_total 8998
telemt_upstream_connect_success_total 8959
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 8998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4064
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4890
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_reconnect_attempts_total 6985
telemt_me_reconnect_success_total 6953
telemt_me_reader_eof_total 7401
telemt_me_idle_close_by_peer_total 7401
telemt_me_route_drop_no_conn_total 95543
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 297000
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1184
telemt_desync_full_logged_total 379
telemt_desync_suppressed_total 805
telemt_desync_frames_bucket_total{bucket="1_2"} 349
telemt_desync_frames_bucket_total{bucket="3_10"} 489
telemt_desync_frames_bucket_total{bucket="gt_10"} 346
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7023
telemt_me_writer_restored_same_endpoint_total 6945
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 297007
telemt_user_connections_current{user="hello"} 745
telemt_user_octets_from_client{user="hello"} 3488110160 (3.25 GB)
telemt_user_octets_to_client{user="hello"} 111702051672 (104.03 GB)
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 119
```