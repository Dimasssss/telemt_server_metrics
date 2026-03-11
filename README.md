# Server Metrics 2026-03-11 12:02:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 77753.6 (21h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1773218
telemt_connections_bad_total 25419
telemt_handshake_timeouts_total 45806
telemt_upstream_connect_attempt_total 16198
telemt_upstream_connect_success_total 16189
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 16198
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8164
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7956
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 829
telemt_me_reconnect_attempts_total 25075
telemt_me_reconnect_success_total 12252
telemt_me_reader_eof_total 13256
telemt_me_idle_close_by_peer_total 13256
telemt_me_route_drop_no_conn_total 651813
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1615725
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8456
telemt_desync_full_logged_total 2276
telemt_desync_suppressed_total 6180
telemt_desync_frames_bucket_total{bucket="1_2"} 2119
telemt_desync_frames_bucket_total{bucket="3_10"} 3238
telemt_desync_frames_bucket_total{bucket="gt_10"} 3099
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 12781
telemt_me_refill_failed_total 398
telemt_me_writer_restored_same_endpoint_total 12246
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 529
telemt_user_connections_total{user="hello"} 1614271
telemt_user_connections_current{user="hello"} 1425
telemt_user_octets_from_client{user="hello"} 20811205744 (19.38 GB)
telemt_user_octets_to_client{user="hello"} 459165254628 (427.63 GB)
telemt_user_unique_ips_current{user="hello"} 376
telemt_user_unique_ips_recent_window{user="hello"} 226
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 77810.4 (21h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 669427
telemt_connections_bad_total 12240
telemt_handshake_timeouts_total 42536
telemt_upstream_connect_attempt_total 25487
telemt_upstream_connect_success_total 22548
telemt_upstream_connect_fail_total 2939
telemt_upstream_connect_attempts_per_request{bucket="1"} 25487
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10351
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9954
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2939
telemt_me_keepalive_timeout_total 2195
telemt_me_reconnect_attempts_total 16550
telemt_me_reconnect_success_total 15699
telemt_me_reader_eof_total 16618
telemt_me_idle_close_by_peer_total 16616
telemt_me_route_drop_no_conn_total 268990
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 567160
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2584
telemt_desync_full_logged_total 813
telemt_desync_suppressed_total 1771
telemt_desync_frames_bucket_total{bucket="1_2"} 829
telemt_desync_frames_bucket_total{bucket="3_10"} 942
telemt_desync_frames_bucket_total{bucket="gt_10"} 813
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 15895
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 15677
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 196
telemt_user_connections_total{user="hello"} 569385
telemt_user_connections_current{user="hello"} 560
telemt_user_octets_from_client{user="hello"} 6058916398 (5.64 GB)
telemt_user_octets_to_client{user="hello"} 161175281904 (150.11 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 77810.3 (21h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1169159
telemt_connections_bad_total 7892
telemt_handshake_timeouts_total 109968
telemt_upstream_connect_attempt_total 20919
telemt_upstream_connect_success_total 20666
telemt_upstream_connect_fail_total 253
telemt_upstream_connect_attempts_per_request{bucket="1"} 20919
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11260
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9305
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 253
telemt_me_keepalive_timeout_total 842
telemt_me_reconnect_attempts_total 29308
telemt_me_reconnect_success_total 15677
telemt_me_reader_eof_total 16835
telemt_me_idle_close_by_peer_total 16835
telemt_me_route_drop_no_conn_total 391402
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1005513
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2707
telemt_desync_full_logged_total 806
telemt_desync_suppressed_total 1901
telemt_desync_frames_bucket_total{bucket="1_2"} 638
telemt_desync_frames_bucket_total{bucket="3_10"} 1017
telemt_desync_frames_bucket_total{bucket="gt_10"} 1052
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 16309
telemt_me_refill_failed_total 422
telemt_me_writer_restored_same_endpoint_total 15666
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 632
telemt_user_connections_total{user="hello"} 1006256
telemt_user_connections_current{user="hello"} 766
telemt_user_octets_from_client{user="hello"} 11688356441 (10.89 GB)
telemt_user_octets_to_client{user="hello"} 303795259297 (282.93 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 77810.6 (21h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 842052
telemt_connections_bad_total 73041
telemt_handshake_timeouts_total 76392
telemt_upstream_connect_attempt_total 21052
telemt_upstream_connect_success_total 21051
telemt_upstream_connect_attempts_per_request{bucket="1"} 21051
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11569
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9478
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 848
telemt_me_reconnect_attempts_total 18224
telemt_me_reconnect_success_total 17160
telemt_me_reader_eof_total 18213
telemt_me_idle_close_by_peer_total 18212
telemt_me_seq_mismatch_total 15
telemt_me_route_drop_no_conn_total 268575
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 668720
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1441
telemt_desync_full_logged_total 558
telemt_desync_suppressed_total 883
telemt_desync_frames_bucket_total{bucket="1_2"} 513
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 405
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 17369
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 17134
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 668089
telemt_user_connections_current{user="hello"} 512
telemt_user_octets_from_client{user="hello"} 7592512876 (7.07 GB)
telemt_user_octets_to_client{user="hello"} 189791934744 (176.76 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 77810.5 (21h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 908114
telemt_connections_bad_total 6244
telemt_handshake_timeouts_total 8689
telemt_upstream_connect_attempt_total 21377
telemt_upstream_connect_success_total 21284
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 21377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10911
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10196
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 896
telemt_me_reconnect_attempts_total 21332
telemt_me_reconnect_success_total 17271
telemt_me_reader_eof_total 18220
telemt_me_idle_close_by_peer_total 18220
telemt_me_route_drop_no_conn_total 318843
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 824968
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3397
telemt_desync_full_logged_total 1256
telemt_desync_suppressed_total 2141
telemt_desync_frames_bucket_total{bucket="1_2"} 1156
telemt_desync_frames_bucket_total{bucket="3_10"} 1322
telemt_desync_frames_bucket_total{bucket="gt_10"} 919
telemt_pool_swap_total 53
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 17616
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 17271
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 345
telemt_user_connections_total{user="hello"} 824724
telemt_user_connections_current{user="hello"} 802
telemt_user_octets_from_client{user="hello"} 12315743103 (11.47 GB)
telemt_user_octets_to_client{user="hello"} 299436484998 (278.87 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 125
```