# Server Metrics 2026-03-14 07:51:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 179586.4 (49h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5071750
telemt_connections_bad_total 40355
telemt_handshake_timeouts_total 115785
telemt_upstream_connect_attempt_total 37793
telemt_upstream_connect_success_total 37548
telemt_upstream_connect_fail_total 245
telemt_upstream_connect_attempts_per_request{bucket="1"} 37793
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20372
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17026
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 245
telemt_me_keepalive_timeout_total 7367
telemt_me_reconnect_attempts_total 37493
telemt_me_reconnect_success_total 26283
telemt_me_reader_eof_total 28207
telemt_me_idle_close_by_peer_total 28206
telemt_me_route_drop_no_conn_total 1919059
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4650070
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17702
telemt_desync_full_logged_total 4815
telemt_desync_suppressed_total 12887
telemt_desync_frames_bucket_total{bucket="1_2"} 4409
telemt_desync_frames_bucket_total{bucket="3_10"} 6730
telemt_desync_frames_bucket_total{bucket="gt_10"} 6563
telemt_pool_swap_total 156
telemt_me_writer_removed_unexpected_total 27012
telemt_me_refill_failed_total 345
telemt_me_writer_restored_same_endpoint_total 26270
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 729
telemt_user_connections_total{user="hello"} 4651531
telemt_user_connections_current{user="hello"} 1422
telemt_user_octets_from_client{user="hello"} 71320039444 (66.42 GB)
telemt_user_octets_to_client{user="hello"} 1487256575213 (1.35 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 423
telemt_user_unique_ips_recent_window{user="hello"} 182
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 79250.0 (22h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 866289
telemt_connections_bad_total 53907
telemt_handshake_timeouts_total 15740
telemt_upstream_connect_attempt_total 21246
telemt_upstream_connect_success_total 20971
telemt_upstream_connect_fail_total 274
telemt_upstream_connect_attempts_per_request{bucket="1"} 21245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11435
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9261
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 36
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 239
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 274
telemt_me_keepalive_timeout_total 2147
telemt_me_reconnect_attempts_total 18471
telemt_me_reconnect_success_total 15005
telemt_me_reader_eof_total 15950
telemt_me_idle_close_by_peer_total 15949
telemt_me_route_drop_no_conn_total 286209
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 696194
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2081
telemt_desync_full_logged_total 649
telemt_desync_suppressed_total 1432
telemt_desync_frames_bucket_total{bucket="1_2"} 436
telemt_desync_frames_bucket_total{bucket="3_10"} 918
telemt_desync_frames_bucket_total{bucket="gt_10"} 727
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 15329
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 14997
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 324
telemt_user_connections_total{user="hello"} 698103
telemt_user_connections_current{user="hello"} 499
telemt_user_octets_from_client{user="hello"} 7302350581 (6.80 GB)
telemt_user_octets_to_client{user="hello"} 241452782684 (224.87 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 209206.7 (58h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3627332
telemt_connections_bad_total 42666
telemt_handshake_timeouts_total 238284
telemt_upstream_connect_attempt_total 47277
telemt_upstream_connect_success_total 47256
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 47277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24941
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22064
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 244
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10720
telemt_me_reconnect_attempts_total 41514
telemt_me_reconnect_success_total 36533
telemt_me_reader_eof_total 38790
telemt_me_idle_close_by_peer_total 38789
telemt_me_route_drop_no_conn_total 1242441
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3026728
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9966
telemt_desync_full_logged_total 3351
telemt_desync_suppressed_total 6615
telemt_desync_frames_bucket_total{bucket="1_2"} 1755
telemt_desync_frames_bucket_total{bucket="3_10"} 3606
telemt_desync_frames_bucket_total{bucket="gt_10"} 4605
telemt_pool_swap_total 197
telemt_me_writer_removed_unexpected_total 37040
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 36492
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 507
telemt_user_connections_total{user="hello"} 3025866
telemt_user_connections_current{user="hello"} 810
telemt_user_octets_from_client{user="hello"} 50802807900 (47.31 GB)
telemt_user_octets_to_client{user="hello"} 1082477099829 (1008.14 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 269
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 209209.4 (58h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2414143
telemt_connections_bad_total 23313
telemt_handshake_timeouts_total 291524
telemt_upstream_connect_attempt_total 65220
telemt_upstream_connect_success_total 62727
telemt_upstream_connect_fail_total 2356
telemt_upstream_connect_attempts_per_request{bucket="1"} 64946
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37446
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25115
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2355
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20543
telemt_me_reconnect_attempts_total 54377
telemt_me_reconnect_success_total 45295
telemt_me_reader_eof_total 48538
telemt_me_idle_close_by_peer_total 48531
telemt_me_route_drop_no_conn_total 811594
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1900224
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3929
telemt_desync_full_logged_total 1279
telemt_desync_suppressed_total 2650
telemt_desync_frames_bucket_total{bucket="1_2"} 1080
telemt_desync_frames_bucket_total{bucket="3_10"} 1618
telemt_desync_frames_bucket_total{bucket="gt_10"} 1231
telemt_pool_swap_total 185
telemt_me_writer_removed_unexpected_total 45968
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 45271
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 673
telemt_user_connections_total{user="hello"} 1906330
telemt_user_connections_current{user="hello"} 388
telemt_user_octets_from_client{user="hello"} 28594563591 (26.63 GB)
telemt_user_octets_to_client{user="hello"} 696427509782 (648.60 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 78642.7 (21h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 840401
telemt_connections_bad_total 8431
telemt_handshake_timeouts_total 9918
telemt_upstream_connect_attempt_total 20061
telemt_upstream_connect_success_total 19524
telemt_upstream_connect_fail_total 537
telemt_upstream_connect_attempts_per_request{bucket="1"} 20061
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9349
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10149
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 537
telemt_me_keepalive_timeout_total 1591
telemt_me_reconnect_attempts_total 64777
telemt_me_reconnect_success_total 15596
telemt_me_reader_eof_total 17505
telemt_me_idle_close_by_peer_total 17504
telemt_me_route_drop_no_conn_total 323477
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 785299
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1965
telemt_desync_full_logged_total 626
telemt_desync_suppressed_total 1339
telemt_desync_frames_bucket_total{bucket="1_2"} 615
telemt_desync_frames_bucket_total{bucket="3_10"} 747
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 17267
telemt_me_refill_failed_total 1532
telemt_me_writer_restored_same_endpoint_total 15591
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1671
telemt_user_connections_total{user="hello"} 785157
telemt_user_connections_current{user="hello"} 656
telemt_user_octets_from_client{user="hello"} 13886132780 (12.93 GB)
telemt_user_octets_to_client{user="hello"} 264395506940 (246.24 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 78
```