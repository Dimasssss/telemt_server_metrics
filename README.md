# Server Metrics 2026-03-11 06:36:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 58184.8 (16h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1150156
telemt_connections_bad_total 13234
telemt_handshake_timeouts_total 38619
telemt_upstream_connect_attempt_total 12266
telemt_upstream_connect_success_total 12257
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 12266
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6035
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 693
telemt_me_reconnect_attempts_total 20989
telemt_me_reconnect_success_total 9306
telemt_me_reader_eof_total 10117
telemt_me_idle_close_by_peer_total 10117
telemt_me_route_drop_no_conn_total 423202
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1034673
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4906
telemt_desync_full_logged_total 1375
telemt_desync_suppressed_total 3531
telemt_desync_frames_bucket_total{bucket="1_2"} 1334
telemt_desync_frames_bucket_total{bucket="3_10"} 1842
telemt_desync_frames_bucket_total{bucket="gt_10"} 1730
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 9759
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 9300
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 453
telemt_user_connections_total{user="hello"} 1034339
telemt_user_connections_current{user="hello"} 1089
telemt_user_octets_from_client{user="hello"} 13738534820 (12.80 GB)
telemt_user_octets_to_client{user="hello"} 303330958104 (282.50 GB)
telemt_user_unique_ips_current{user="hello"} 313
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 58241.7 (16h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 442977
telemt_connections_bad_total 5073
telemt_handshake_timeouts_total 21791
telemt_upstream_connect_attempt_total 20967
telemt_upstream_connect_success_total 18056
telemt_upstream_connect_fail_total 2911
telemt_upstream_connect_attempts_per_request{bucket="1"} 20967
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8113
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7700
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2911
telemt_me_keepalive_timeout_total 2016
telemt_me_reconnect_attempts_total 13016
telemt_me_reconnect_success_total 12191
telemt_me_reader_eof_total 12887
telemt_me_idle_close_by_peer_total 12885
telemt_me_route_drop_no_conn_total 200882
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 378833
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1938
telemt_desync_full_logged_total 584
telemt_desync_suppressed_total 1354
telemt_desync_frames_bucket_total{bucket="1_2"} 617
telemt_desync_frames_bucket_total{bucket="3_10"} 696
telemt_desync_frames_bucket_total{bucket="gt_10"} 625
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 12334
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 12169
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 381103
telemt_user_connections_current{user="hello"} 391
telemt_user_octets_from_client{user="hello"} 3811857894 (3.55 GB)
telemt_user_octets_to_client{user="hello"} 94909516060 (88.39 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 58241.5 (16h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 754235
telemt_connections_bad_total 6460
telemt_handshake_timeouts_total 41213
telemt_upstream_connect_attempt_total 15612
telemt_upstream_connect_success_total 15409
telemt_upstream_connect_fail_total 203
telemt_upstream_connect_attempts_per_request{bucket="1"} 15612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8402
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6921
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 203
telemt_me_keepalive_timeout_total 696
telemt_me_reconnect_attempts_total 22496
telemt_me_reconnect_success_total 11423
telemt_me_reader_eof_total 12318
telemt_me_idle_close_by_peer_total 12318
telemt_me_route_drop_no_conn_total 254738
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 674421
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1915
telemt_desync_full_logged_total 552
telemt_desync_suppressed_total 1363
telemt_desync_frames_bucket_total{bucket="1_2"} 442
telemt_desync_frames_bucket_total{bucket="3_10"} 696
telemt_desync_frames_bucket_total{bucket="gt_10"} 777
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 11916
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 11412
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 493
telemt_user_connections_total{user="hello"} 675252
telemt_user_connections_current{user="hello"} 626
telemt_user_octets_from_client{user="hello"} 7992083641 (7.44 GB)
telemt_user_octets_to_client{user="hello"} 200385853793 (186.62 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 58242.0 (16h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 573955
telemt_connections_bad_total 54627
telemt_handshake_timeouts_total 58665
telemt_upstream_connect_attempt_total 16556
telemt_upstream_connect_success_total 16556
telemt_upstream_connect_attempts_per_request{bucket="1"} 16556
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9279
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7273
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 650
telemt_me_reconnect_attempts_total 14689
telemt_me_reconnect_success_total 13643
telemt_me_reader_eof_total 14484
telemt_me_idle_close_by_peer_total 14484
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 172932
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 444579
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 937
telemt_desync_full_logged_total 390
telemt_desync_suppressed_total 547
telemt_desync_frames_bucket_total{bucket="1_2"} 341
telemt_desync_frames_bucket_total{bucket="3_10"} 348
telemt_desync_frames_bucket_total{bucket="gt_10"} 248
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 13801
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 13621
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 444125
telemt_user_connections_current{user="hello"} 473
telemt_user_octets_from_client{user="hello"} 5338004104 (4.97 GB)
telemt_user_octets_to_client{user="hello"} 121969892276 (113.59 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 58241.7 (16h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 600225
telemt_connections_bad_total 5964
telemt_handshake_timeouts_total 4229
telemt_upstream_connect_attempt_total 16522
telemt_upstream_connect_success_total 16454
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 16522
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8449
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7870
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 133
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 675
telemt_me_reconnect_attempts_total 17209
telemt_me_reconnect_success_total 13423
telemt_me_reader_eof_total 14182
telemt_me_idle_close_by_peer_total 14182
telemt_me_route_drop_no_conn_total 197473
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 546228
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2563
telemt_desync_full_logged_total 991
telemt_desync_suppressed_total 1572
telemt_desync_frames_bucket_total{bucket="1_2"} 920
telemt_desync_frames_bucket_total{bucket="3_10"} 1096
telemt_desync_frames_bucket_total{bucket="gt_10"} 547
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 13714
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 13423
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 291
telemt_user_connections_total{user="hello"} 545962
telemt_user_connections_current{user="hello"} 534
telemt_user_octets_from_client{user="hello"} 9541634347 (8.89 GB)
telemt_user_octets_to_client{user="hello"} 196143885610 (182.67 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 78
```