# Server Metrics 2026-03-10 17:58:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 12706.6 (3h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 423789
telemt_connections_bad_total 7975
telemt_handshake_timeouts_total 1977
telemt_upstream_connect_attempt_total 2446
telemt_upstream_connect_success_total 2437
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1241
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 269
telemt_me_reconnect_attempts_total 11000
telemt_me_reconnect_success_total 1733
telemt_me_reader_eof_total 1999
telemt_me_idle_close_by_peer_total 1999
telemt_me_route_drop_no_conn_total 178914
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 401396
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1995
telemt_desync_full_logged_total 551
telemt_desync_suppressed_total 1444
telemt_desync_frames_bucket_total{bucket="1_2"} 525
telemt_desync_frames_bucket_total{bucket="3_10"} 764
telemt_desync_frames_bucket_total{bucket="gt_10"} 706
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2025
telemt_me_refill_failed_total 289
telemt_me_writer_restored_same_endpoint_total 1727
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 292
telemt_user_connections_total{user="hello"} 401319
telemt_user_connections_current{user="hello"} 1312
telemt_user_octets_from_client{user="hello"} 5329605288 (4.96 GB)
telemt_user_octets_to_client{user="hello"} 118077648604 (109.97 GB)
telemt_user_unique_ips_current{user="hello"} 351
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 12763.1 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 164429
telemt_connections_bad_total 1699
telemt_handshake_timeouts_total 10963
telemt_upstream_connect_attempt_total 2875
telemt_upstream_connect_success_total 2860
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 2875
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1479
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1372
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 2179
telemt_me_reconnect_success_total 2167
telemt_me_reader_eof_total 2249
telemt_me_idle_close_by_peer_total 2249
telemt_me_route_drop_no_conn_total 47988
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 143230
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 644
telemt_desync_full_logged_total 193
telemt_desync_suppressed_total 451
telemt_desync_frames_bucket_total{bucket="1_2"} 247
telemt_desync_frames_bucket_total{bucket="3_10"} 216
telemt_desync_frames_bucket_total{bucket="gt_10"} 181
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2180
telemt_me_writer_restored_same_endpoint_total 2146
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 143208
telemt_user_connections_current{user="hello"} 502
telemt_user_octets_from_client{user="hello"} 1809727668 (1.69 GB)
telemt_user_octets_to_client{user="hello"} 38333939976 (35.70 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 12763.1 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 313820
telemt_connections_bad_total 966
telemt_handshake_timeouts_total 31221
telemt_upstream_connect_attempt_total 4202
telemt_upstream_connect_success_total 4136
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 4202
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2551
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1569
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 3584
telemt_me_reconnect_success_total 2388
telemt_me_reader_eof_total 2508
telemt_me_idle_close_by_peer_total 2508
telemt_me_route_drop_no_conn_total 102324
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 258458
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 822
telemt_desync_full_logged_total 239
telemt_desync_suppressed_total 583
telemt_desync_frames_bucket_total{bucket="1_2"} 208
telemt_desync_frames_bucket_total{bucket="3_10"} 286
telemt_desync_frames_bucket_total{bucket="gt_10"} 328
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2463
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2377
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 259424
telemt_user_connections_current{user="hello"} 760
telemt_user_octets_from_client{user="hello"} 3536443521 (3.29 GB)
telemt_user_octets_to_client{user="hello"} 78914659001 (73.50 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 228
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 12763.6 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202667
telemt_connections_bad_total 12392
telemt_handshake_timeouts_total 19222
telemt_upstream_connect_attempt_total 3347
telemt_upstream_connect_success_total 3347
telemt_upstream_connect_attempts_per_request{bucket="1"} 3347
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1786
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1561
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 2664
telemt_me_reconnect_success_total 2648
telemt_me_reader_eof_total 2743
telemt_me_idle_close_by_peer_total 2743
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 65732
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162693
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 490
telemt_desync_full_logged_total 193
telemt_desync_suppressed_total 297
telemt_desync_frames_bucket_total{bucket="1_2"} 160
telemt_desync_frames_bucket_total{bucket="3_10"} 181
telemt_desync_frames_bucket_total{bucket="gt_10"} 149
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2671
telemt_me_writer_restored_same_endpoint_total 2636
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 162514
telemt_user_connections_current{user="hello"} 584
telemt_user_octets_from_client{user="hello"} 2634382872 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 45730644476 (42.59 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 12763.1 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 214394
telemt_connections_bad_total 796
telemt_handshake_timeouts_total 1644
telemt_upstream_connect_attempt_total 3825
telemt_upstream_connect_success_total 3813
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 3825
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1968
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1816
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 79
telemt_me_reconnect_attempts_total 3118
telemt_me_reconnect_success_total 3098
telemt_me_reader_eof_total 3181
telemt_me_idle_close_by_peer_total 3181
telemt_me_route_drop_no_conn_total 78427
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 201798
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1073
telemt_desync_full_logged_total 381
telemt_desync_suppressed_total 692
telemt_desync_frames_bucket_total{bucket="1_2"} 441
telemt_desync_frames_bucket_total{bucket="3_10"} 456
telemt_desync_frames_bucket_total{bucket="gt_10"} 176
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 3128
telemt_me_writer_restored_same_endpoint_total 3098
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 201733
telemt_user_connections_current{user="hello"} 698
telemt_user_octets_from_client{user="hello"} 4466994696 (4.16 GB)
telemt_user_octets_to_client{user="hello"} 58619465872 (54.59 GB)
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 99
```