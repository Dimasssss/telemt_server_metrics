# Server Metrics 2026-03-11 10:31:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 72241.0 (20h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1587785
telemt_connections_bad_total 24742
telemt_handshake_timeouts_total 41606
telemt_upstream_connect_attempt_total 14975
telemt_upstream_connect_success_total 14966
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 14975
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7585
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7314
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 799
telemt_me_reconnect_attempts_total 22998
telemt_me_reconnect_success_total 11306
telemt_me_reader_eof_total 12237
telemt_me_idle_close_by_peer_total 12237
telemt_me_route_drop_no_conn_total 585354
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1441210
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7224
telemt_desync_full_logged_total 1983
telemt_desync_suppressed_total 5241
telemt_desync_frames_bucket_total{bucket="1_2"} 1895
telemt_desync_frames_bucket_total{bucket="3_10"} 2723
telemt_desync_frames_bucket_total{bucket="gt_10"} 2606
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 11782
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 11300
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 476
telemt_user_connections_total{user="hello"} 1439791
telemt_user_connections_current{user="hello"} 1158
telemt_user_octets_from_client{user="hello"} 18700401460 (17.42 GB)
telemt_user_octets_to_client{user="hello"} 411177116708 (382.94 GB)
telemt_user_unique_ips_current{user="hello"} 335
telemt_user_unique_ips_recent_window{user="hello"} 194
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 72297.8 (20h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 608355
telemt_connections_bad_total 10183
telemt_handshake_timeouts_total 37484
telemt_upstream_connect_attempt_total 24049
telemt_upstream_connect_success_total 21117
telemt_upstream_connect_fail_total 2932
telemt_upstream_connect_attempts_per_request{bucket="1"} 24049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9655
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9219
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2932
telemt_me_keepalive_timeout_total 2155
telemt_me_reconnect_attempts_total 15383
telemt_me_reconnect_success_total 14538
telemt_me_reader_eof_total 15404
telemt_me_idle_close_by_peer_total 15402
telemt_me_route_drop_no_conn_total 249175
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 514791
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2314
telemt_desync_full_logged_total 719
telemt_desync_suppressed_total 1595
telemt_desync_frames_bucket_total{bucket="1_2"} 768
telemt_desync_frames_bucket_total{bucket="3_10"} 830
telemt_desync_frames_bucket_total{bucket="gt_10"} 716
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 14718
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 14516
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 517017
telemt_user_connections_current{user="hello"} 488
telemt_user_octets_from_client{user="hello"} 5083070166 (4.73 GB)
telemt_user_octets_to_client{user="hello"} 144266666832 (134.36 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 72297.6 (20h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1052821
telemt_connections_bad_total 7700
telemt_handshake_timeouts_total 101776
telemt_upstream_connect_attempt_total 19561
telemt_upstream_connect_success_total 19317
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 19561
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10523
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8702
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_keepalive_timeout_total 809
telemt_me_reconnect_attempts_total 28224
telemt_me_reconnect_success_total 14605
telemt_me_reader_eof_total 15700
telemt_me_idle_close_by_peer_total 15700
telemt_me_route_drop_no_conn_total 348667
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 903112
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2551
telemt_desync_full_logged_total 754
telemt_desync_suppressed_total 1797
telemt_desync_frames_bucket_total{bucket="1_2"} 609
telemt_desync_frames_bucket_total{bucket="3_10"} 944
telemt_desync_frames_bucket_total{bucket="gt_10"} 998
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 15218
telemt_me_refill_failed_total 422
telemt_me_writer_restored_same_endpoint_total 14594
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 613
telemt_user_connections_total{user="hello"} 903935
telemt_user_connections_current{user="hello"} 705
telemt_user_octets_from_client{user="hello"} 10616091809 (9.89 GB)
telemt_user_octets_to_client{user="hello"} 275743884253 (256.81 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 72298.2 (20h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 766679
telemt_connections_bad_total 68020
telemt_handshake_timeouts_total 73189
telemt_upstream_connect_attempt_total 19802
telemt_upstream_connect_success_total 19802
telemt_upstream_connect_attempts_per_request{bucket="1"} 19802
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10947
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8851
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 769
telemt_me_reconnect_attempts_total 17239
telemt_me_reconnect_success_total 16182
telemt_me_reader_eof_total 17186
telemt_me_idle_close_by_peer_total 17185
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 241690
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 602877
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1315
telemt_desync_full_logged_total 504
telemt_desync_suppressed_total 811
telemt_desync_frames_bucket_total{bucket="1_2"} 456
telemt_desync_frames_bucket_total{bucket="3_10"} 488
telemt_desync_frames_bucket_total{bucket="gt_10"} 371
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 16373
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 16158
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 191
telemt_user_connections_total{user="hello"} 602248
telemt_user_connections_current{user="hello"} 544
telemt_user_octets_from_client{user="hello"} 6922244440 (6.45 GB)
telemt_user_octets_to_client{user="hello"} 173499105912 (161.58 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 72297.8 (20h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 817603
telemt_connections_bad_total 6086
telemt_handshake_timeouts_total 7772
telemt_upstream_connect_attempt_total 19418
telemt_upstream_connect_success_total 19336
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 19418
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9961
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9211
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 813
telemt_me_reconnect_attempts_total 19394
telemt_me_reconnect_success_total 15598
telemt_me_reader_eof_total 16491
telemt_me_idle_close_by_peer_total 16491
telemt_me_route_drop_no_conn_total 283529
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 742168
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3085
telemt_desync_full_logged_total 1153
telemt_desync_suppressed_total 1932
telemt_desync_frames_bucket_total{bucket="1_2"} 1069
telemt_desync_frames_bucket_total{bucket="3_10"} 1249
telemt_desync_frames_bucket_total{bucket="gt_10"} 767
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 15913
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 15598
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 315
telemt_user_connections_total{user="hello"} 741896
telemt_user_connections_current{user="hello"} 656
telemt_user_octets_from_client{user="hello"} 11356475315 (10.58 GB)
telemt_user_octets_to_client{user="hello"} 271376826454 (252.74 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 89
```