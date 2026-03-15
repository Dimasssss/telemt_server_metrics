# Server Metrics 2026-03-15 09:44:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 41389.7 (11h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 940454
telemt_connections_bad_total 51947
telemt_handshake_timeouts_total 7040
telemt_upstream_connect_attempt_total 8276
telemt_upstream_connect_success_total 8241
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 8276
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4324
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3900
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6226
telemt_me_reconnect_success_total 6192
telemt_me_reader_eof_total 6554
telemt_me_idle_close_by_peer_total 6554
telemt_me_route_drop_no_conn_total 309492
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 792470
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2766
telemt_desync_full_logged_total 819
telemt_desync_suppressed_total 1947
telemt_desync_frames_bucket_total{bucket="1_2"} 650
telemt_desync_frames_bucket_total{bucket="3_10"} 1062
telemt_desync_frames_bucket_total{bucket="gt_10"} 1054
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 6280
telemt_me_writer_restored_same_endpoint_total 6181
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 792480
telemt_user_connections_current{user="hello"} 2038
telemt_user_octets_from_client{user="hello"} 11453525196 (10.67 GB)
telemt_user_octets_to_client{user="hello"} 304240233092 (283.35 GB)
telemt_user_unique_ips_current{user="hello"} 581
telemt_user_unique_ips_recent_window{user="hello"} 282
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 41390.3 (11h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 371020
telemt_connections_bad_total 20834
telemt_handshake_timeouts_total 14569
telemt_upstream_connect_attempt_total 10934
telemt_upstream_connect_success_total 10878
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 10934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5896
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4890
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 8556
telemt_me_reconnect_success_total 8503
telemt_me_reader_eof_total 9006
telemt_me_idle_close_by_peer_total 9006
telemt_me_route_drop_no_conn_total 94172
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 293194
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1045
telemt_desync_full_logged_total 362
telemt_desync_suppressed_total 683
telemt_desync_frames_bucket_total{bucket="1_2"} 337
telemt_desync_frames_bucket_total{bucket="3_10"} 389
telemt_desync_frames_bucket_total{bucket="gt_10"} 319
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 8579
telemt_me_writer_restored_same_endpoint_total 8495
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 293482
telemt_user_connections_current{user="hello"} 680
telemt_user_octets_from_client{user="hello"} 4299069291 (4.00 GB)
telemt_user_octets_to_client{user="hello"} 110833371144 (103.22 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 41390.5 (11h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 674029
telemt_connections_bad_total 22431
telemt_handshake_timeouts_total 69156
telemt_upstream_connect_attempt_total 9211
telemt_upstream_connect_success_total 9172
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 9211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4331
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_reconnect_attempts_total 7153
telemt_me_reconnect_success_total 7107
telemt_me_reader_eof_total 7521
telemt_me_idle_close_by_peer_total 7521
telemt_me_route_drop_no_conn_total 195258
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 514320
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1085
telemt_desync_full_logged_total 408
telemt_desync_suppressed_total 677
telemt_desync_frames_bucket_total{bucket="1_2"} 235
telemt_desync_frames_bucket_total{bucket="3_10"} 387
telemt_desync_frames_bucket_total{bucket="gt_10"} 463
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7195
telemt_me_writer_restored_same_endpoint_total 7088
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 513751
telemt_user_connections_current{user="hello"} 1141
telemt_user_octets_from_client{user="hello"} 7727383260 (7.20 GB)
telemt_user_octets_to_client{user="hello"} 205795617164 (191.66 GB)
telemt_user_unique_ips_current{user="hello"} 354
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 41390.3 (11h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 390862
telemt_connections_bad_total 53190
telemt_handshake_timeouts_total 24356
telemt_upstream_connect_attempt_total 12826
telemt_upstream_connect_success_total 12516
telemt_upstream_connect_fail_total 310
telemt_upstream_connect_attempts_per_request{bucket="1"} 12826
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5866
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6647
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 310
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 28162
telemt_me_reconnect_success_total 10459
telemt_me_reader_eof_total 11324
telemt_me_idle_close_by_peer_total 11324
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 106607
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 292387
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 715
telemt_desync_full_logged_total 177
telemt_desync_suppressed_total 538
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 297
telemt_desync_frames_bucket_total{bucket="gt_10"} 249
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 11103
telemt_me_refill_failed_total 553
telemt_me_writer_restored_same_endpoint_total 10429
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 644
telemt_user_connections_total{user="hello"} 292297
telemt_user_connections_current{user="hello"} 642
telemt_user_octets_from_client{user="hello"} 3325143884 (3.10 GB)
telemt_user_octets_to_client{user="hello"} 94582167688 (88.09 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 41391.5 (11h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 372629
telemt_connections_bad_total 3872
telemt_handshake_timeouts_total 4152
telemt_upstream_connect_attempt_total 9202
telemt_upstream_connect_success_total 9161
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 9202
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4993
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_reconnect_attempts_total 7143
telemt_me_reconnect_success_total 7109
telemt_me_reader_eof_total 7561
telemt_me_idle_close_by_peer_total 7561
telemt_me_route_drop_no_conn_total 100294
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 312780
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1215
telemt_desync_full_logged_total 392
telemt_desync_suppressed_total 823
telemt_desync_frames_bucket_total{bucket="1_2"} 363
telemt_desync_frames_bucket_total{bucket="3_10"} 496
telemt_desync_frames_bucket_total{bucket="gt_10"} 356
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7183
telemt_me_writer_restored_same_endpoint_total 7101
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 312785
telemt_user_connections_current{user="hello"} 839
telemt_user_octets_from_client{user="hello"} 3675209848 (3.42 GB)
telemt_user_octets_to_client{user="hello"} 115152971260 (107.24 GB)
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 119
```