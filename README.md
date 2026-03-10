# Server Metrics 2026-03-10 22:29:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 28922.0 (8h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 735057
telemt_connections_bad_total 8896
telemt_handshake_timeouts_total 8335
telemt_upstream_connect_attempt_total 6223
telemt_upstream_connect_success_total 6214
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 6223
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3086
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3071
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 357
telemt_me_reconnect_attempts_total 16330
telemt_me_reconnect_success_total 4671
telemt_me_reader_eof_total 5152
telemt_me_idle_close_by_peer_total 5152
telemt_me_route_drop_no_conn_total 306395
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 695035
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3447
telemt_desync_full_logged_total 963
telemt_desync_suppressed_total 2484
telemt_desync_frames_bucket_total{bucket="1_2"} 994
telemt_desync_frames_bucket_total{bucket="3_10"} 1291
telemt_desync_frames_bucket_total{bucket="gt_10"} 1162
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 5073
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 4665
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 402
telemt_user_connections_total{user="hello"} 694837
telemt_user_connections_current{user="hello"} 512
telemt_user_octets_from_client{user="hello"} 9983139260 (9.30 GB)
telemt_user_octets_to_client{user="hello"} 210809252888 (196.33 GB)
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 28978.5 (8h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 318771
telemt_connections_bad_total 2363
telemt_handshake_timeouts_total 17577
telemt_upstream_connect_attempt_total 12783
telemt_upstream_connect_success_total 9916
telemt_upstream_connect_fail_total 2867
telemt_upstream_connect_attempts_per_request{bucket="1"} 12783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3500
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2867
telemt_me_keepalive_timeout_total 1375
telemt_me_reconnect_attempts_total 6264
telemt_me_reconnect_success_total 5458
telemt_me_reader_eof_total 5727
telemt_me_idle_close_by_peer_total 5725
telemt_me_route_drop_no_conn_total 166605
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 268853
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1610
telemt_desync_full_logged_total 447
telemt_desync_suppressed_total 1163
telemt_desync_frames_bucket_total{bucket="1_2"} 493
telemt_desync_frames_bucket_total{bucket="3_10"} 572
telemt_desync_frames_bucket_total{bucket="gt_10"} 545
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 5546
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 5437
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 271126
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 2662426538 (2.48 GB)
telemt_user_octets_to_client{user="hello"} 63819758052 (59.44 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 28978.3 (8h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 526481
telemt_connections_bad_total 3363
telemt_handshake_timeouts_total 33728
telemt_upstream_connect_attempt_total 8004
telemt_upstream_connect_success_total 7885
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 8004
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4577
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3249
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 214
telemt_me_reconnect_attempts_total 16356
telemt_me_reconnect_success_total 5301
telemt_me_reader_eof_total 5835
telemt_me_idle_close_by_peer_total 5835
telemt_me_route_drop_no_conn_total 182910
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 461069
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1471
telemt_desync_full_logged_total 415
telemt_desync_suppressed_total 1056
telemt_desync_frames_bucket_total{bucket="1_2"} 334
telemt_desync_frames_bucket_total{bucket="3_10"} 513
telemt_desync_frames_bucket_total{bucket="gt_10"} 624
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 5729
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 5290
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 428
telemt_user_connections_total{user="hello"} 462002
telemt_user_connections_current{user="hello"} 251
telemt_user_octets_from_client{user="hello"} 6619849033 (6.17 GB)
telemt_user_octets_to_client{user="hello"} 148061514093 (137.89 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 28978.8 (8h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 369239
telemt_connections_bad_total 27917
telemt_handshake_timeouts_total 32971
telemt_upstream_connect_attempt_total 8050
telemt_upstream_connect_success_total 8050
telemt_upstream_connect_attempts_per_request{bucket="1"} 8050
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4446
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3603
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 172
telemt_me_reconnect_attempts_total 7564
telemt_me_reconnect_success_total 6540
telemt_me_reader_eof_total 6877
telemt_me_idle_close_by_peer_total 6877
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 118530
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 295488
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 687
telemt_desync_full_logged_total 279
telemt_desync_suppressed_total 408
telemt_desync_frames_bucket_total{bucket="1_2"} 266
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 178
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 6640
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 6526
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 295163
telemt_user_connections_current{user="hello"} 233
telemt_user_octets_from_client{user="hello"} 4043162180 (3.77 GB)
telemt_user_octets_to_client{user="hello"} 86759627556 (80.80 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 28978.6 (8h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 389815
telemt_connections_bad_total 2532
telemt_handshake_timeouts_total 2565
telemt_upstream_connect_attempt_total 9009
telemt_upstream_connect_success_total 8973
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 9009
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4172
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 193
telemt_me_reconnect_attempts_total 11189
telemt_me_reconnect_success_total 7430
telemt_me_reader_eof_total 7799
telemt_me_idle_close_by_peer_total 7799
telemt_me_route_drop_no_conn_total 136567
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 363175
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2135
telemt_desync_full_logged_total 812
telemt_desync_suppressed_total 1323
telemt_desync_frames_bucket_total{bucket="1_2"} 790
telemt_desync_frames_bucket_total{bucket="3_10"} 912
telemt_desync_frames_bucket_total{bucket="gt_10"} 433
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 7652
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 7430
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 222
telemt_user_connections_total{user="hello"} 363002
telemt_user_connections_current{user="hello"} 252
telemt_user_octets_from_client{user="hello"} 6424651100 (5.98 GB)
telemt_user_octets_to_client{user="hello"} 137276769204 (127.85 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 40
```