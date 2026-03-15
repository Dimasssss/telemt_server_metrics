# Server Metrics 2026-03-15 10:09:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 42925.0 (11h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1013062
telemt_connections_bad_total 57452
telemt_handshake_timeouts_total 7893
telemt_upstream_connect_attempt_total 8584
telemt_upstream_connect_success_total 8546
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 8584
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4028
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6444
telemt_me_reconnect_success_total 6406
telemt_me_reader_eof_total 6776
telemt_me_idle_close_by_peer_total 6776
telemt_me_route_drop_no_conn_total 334393
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 854786
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3107
telemt_desync_full_logged_total 886
telemt_desync_suppressed_total 2221
telemt_desync_frames_bucket_total{bucket="1_2"} 741
telemt_desync_frames_bucket_total{bucket="3_10"} 1224
telemt_desync_frames_bucket_total{bucket="gt_10"} 1142
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6497
telemt_me_writer_restored_same_endpoint_total 6395
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 854789
telemt_user_connections_current{user="hello"} 2078
telemt_user_octets_from_client{user="hello"} 12361231260 (11.51 GB)
telemt_user_octets_to_client{user="hello"} 328900321556 (306.31 GB)
telemt_user_unique_ips_current{user="hello"} 580
telemt_user_unique_ips_recent_window{user="hello"} 283
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 42925.7 (11h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 399748
telemt_connections_bad_total 22115
telemt_handshake_timeouts_total 16772
telemt_upstream_connect_attempt_total 11375
telemt_upstream_connect_success_total 11315
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 11375
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6122
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5096
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 8903
telemt_me_reconnect_success_total 8846
telemt_me_reader_eof_total 9373
telemt_me_idle_close_by_peer_total 9373
telemt_me_route_drop_no_conn_total 101834
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 315941
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1124
telemt_desync_full_logged_total 389
telemt_desync_suppressed_total 735
telemt_desync_frames_bucket_total{bucket="1_2"} 375
telemt_desync_frames_bucket_total{bucket="3_10"} 412
telemt_desync_frames_bucket_total{bucket="gt_10"} 337
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 8931
telemt_me_writer_restored_same_endpoint_total 8838
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 316226
telemt_user_connections_current{user="hello"} 691
telemt_user_octets_from_client{user="hello"} 4625060231 (4.31 GB)
telemt_user_octets_to_client{user="hello"} 119682877764 (111.46 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 42925.6 (11h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 738119
telemt_connections_bad_total 24844
telemt_handshake_timeouts_total 74233
telemt_upstream_connect_attempt_total 9495
telemt_upstream_connect_success_total 9455
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 9495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4932
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4471
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_reconnect_attempts_total 7347
telemt_me_reconnect_success_total 7300
telemt_me_reader_eof_total 7730
telemt_me_idle_close_by_peer_total 7730
telemt_me_route_drop_no_conn_total 211548
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 554030
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1225
telemt_desync_full_logged_total 454
telemt_desync_suppressed_total 771
telemt_desync_frames_bucket_total{bucket="1_2"} 270
telemt_desync_frames_bucket_total{bucket="3_10"} 444
telemt_desync_frames_bucket_total{bucket="gt_10"} 511
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 7394
telemt_me_writer_restored_same_endpoint_total 7281
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 553455
telemt_user_connections_current{user="hello"} 1223
telemt_user_octets_from_client{user="hello"} 8210812224 (7.65 GB)
telemt_user_octets_to_client{user="hello"} 221653244400 (206.43 GB)
telemt_user_unique_ips_current{user="hello"} 351
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 42925.6 (11h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 418886
telemt_connections_bad_total 54839
telemt_handshake_timeouts_total 25073
telemt_upstream_connect_attempt_total 13063
telemt_upstream_connect_success_total 12741
telemt_upstream_connect_fail_total 322
telemt_upstream_connect_attempts_per_request{bucket="1"} 13063
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6021
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6717
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 322
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 30953
telemt_me_reconnect_success_total 10594
telemt_me_reader_eof_total 11544
telemt_me_idle_close_by_peer_total 11544
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 116456
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 314142
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 740
telemt_desync_full_logged_total 183
telemt_desync_suppressed_total 557
telemt_desync_frames_bucket_total{bucket="1_2"} 178
telemt_desync_frames_bucket_total{bucket="3_10"} 303
telemt_desync_frames_bucket_total{bucket="gt_10"} 259
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 11323
telemt_me_refill_failed_total 636
telemt_me_writer_restored_same_endpoint_total 10564
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 729
telemt_user_connections_total{user="hello"} 314053
telemt_user_connections_current{user="hello"} 553
telemt_user_octets_from_client{user="hello"} 3784538256 (3.52 GB)
telemt_user_octets_to_client{user="hello"} 101452969296 (94.49 GB)
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 42926.6 (11h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 412588
telemt_connections_bad_total 5752
telemt_handshake_timeouts_total 5998
telemt_upstream_connect_attempt_total 9572
telemt_upstream_connect_success_total 9527
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 9572
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4325
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5197
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_reconnect_attempts_total 7422
telemt_me_reconnect_success_total 7386
telemt_me_reader_eof_total 7858
telemt_me_idle_close_by_peer_total 7858
telemt_me_route_drop_no_conn_total 108097
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 341458
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1304
telemt_desync_full_logged_total 419
telemt_desync_suppressed_total 885
telemt_desync_frames_bucket_total{bucket="1_2"} 391
telemt_desync_frames_bucket_total{bucket="3_10"} 527
telemt_desync_frames_bucket_total{bucket="gt_10"} 386
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 7467
telemt_me_writer_restored_same_endpoint_total 7378
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 341462
telemt_user_connections_current{user="hello"} 849
telemt_user_octets_from_client{user="hello"} 4151379116 (3.87 GB)
telemt_user_octets_to_client{user="hello"} 126881583304 (118.17 GB)
telemt_user_unique_ips_current{user="hello"} 223
telemt_user_unique_ips_recent_window{user="hello"} 114
```