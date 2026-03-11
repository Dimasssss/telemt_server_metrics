# Server Metrics 2026-03-11 15:01:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 88478.0 (24h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2156092
telemt_connections_bad_total 34692
telemt_handshake_timeouts_total 52305
telemt_upstream_connect_attempt_total 18670
telemt_upstream_connect_success_total 18658
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 18670
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9401
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9165
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 4861
telemt_me_reconnect_attempts_total 32029
telemt_me_reconnect_success_total 14163
telemt_me_reader_eof_total 15375
telemt_me_idle_close_by_peer_total 15375
telemt_me_route_drop_no_conn_total 797580
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1973234
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10348
telemt_desync_full_logged_total 2803
telemt_desync_suppressed_total 7545
telemt_desync_frames_bucket_total{bucket="1_2"} 2571
telemt_desync_frames_bucket_total{bucket="3_10"} 3988
telemt_desync_frames_bucket_total{bucket="gt_10"} 3789
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 14874
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 14157
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 711
telemt_user_connections_total{user="hello"} 1971714
telemt_user_connections_current{user="hello"} 1424
telemt_user_octets_from_client{user="hello"} 26542454344 (24.72 GB)
telemt_user_octets_to_client{user="hello"} 562032683732 (523.43 GB)
telemt_user_unique_ips_current{user="hello"} 380
telemt_user_unique_ips_recent_window{user="hello"} 228
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 88534.8 (24h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 803262
telemt_connections_bad_total 13250
telemt_handshake_timeouts_total 54653
telemt_upstream_connect_attempt_total 28121
telemt_upstream_connect_success_total 25168
telemt_upstream_connect_fail_total 2953
telemt_upstream_connect_attempts_per_request{bucket="1"} 28121
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11666
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11254
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2953
telemt_me_keepalive_timeout_total 2541
telemt_me_reconnect_attempts_total 19860
telemt_me_reconnect_success_total 17768
telemt_me_reader_eof_total 18826
telemt_me_idle_close_by_peer_total 18823
telemt_me_route_drop_no_conn_total 315029
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 681544
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2866
telemt_desync_full_logged_total 911
telemt_desync_suppressed_total 1955
telemt_desync_frames_bucket_total{bucket="1_2"} 889
telemt_desync_frames_bucket_total{bucket="3_10"} 1033
telemt_desync_frames_bucket_total{bucket="gt_10"} 944
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18029
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 17745
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 261
telemt_user_connections_total{user="hello"} 684020
telemt_user_connections_current{user="hello"} 572
telemt_user_octets_from_client{user="hello"} 7815850710 (7.28 GB)
telemt_user_octets_to_client{user="hello"} 193363869952 (180.08 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 88534.8 (24h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1394825
telemt_connections_bad_total 8521
telemt_handshake_timeouts_total 123153
telemt_upstream_connect_attempt_total 23493
telemt_upstream_connect_success_total 23211
telemt_upstream_connect_fail_total 282
telemt_upstream_connect_attempts_per_request{bucket="1"} 23493
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12523
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10567
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 282
telemt_me_keepalive_timeout_total 1576
telemt_me_reconnect_attempts_total 34669
telemt_me_reconnect_success_total 17659
telemt_me_reader_eof_total 18991
telemt_me_idle_close_by_peer_total 18991
telemt_me_route_drop_no_conn_total 505918
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1211676
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3208
telemt_desync_full_logged_total 949
telemt_desync_suppressed_total 2259
telemt_desync_frames_bucket_total{bucket="1_2"} 791
telemt_desync_frames_bucket_total{bucket="3_10"} 1211
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 18432
telemt_me_refill_failed_total 527
telemt_me_writer_restored_same_endpoint_total 17648
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 773
telemt_user_connections_total{user="hello"} 1211442
telemt_user_connections_current{user="hello"} 748
telemt_user_octets_from_client{user="hello"} 14550003277 (13.55 GB)
telemt_user_octets_to_client{user="hello"} 362528335945 (337.63 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 237
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 88535.1 (24h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 999981
telemt_connections_bad_total 77728
telemt_handshake_timeouts_total 96109
telemt_upstream_connect_attempt_total 23796
telemt_upstream_connect_success_total 23796
telemt_upstream_connect_attempts_per_request{bucket="1"} 23796
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13019
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10772
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 976
telemt_me_reconnect_attempts_total 20441
telemt_me_reconnect_success_total 19367
telemt_me_reader_eof_total 20546
telemt_me_idle_close_by_peer_total 20545
telemt_me_seq_mismatch_total 18
telemt_me_route_drop_no_conn_total 326327
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 798912
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 29
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1691
telemt_desync_full_logged_total 651
telemt_desync_suppressed_total 1040
telemt_desync_frames_bucket_total{bucket="1_2"} 603
telemt_desync_frames_bucket_total{bucket="3_10"} 600
telemt_desync_frames_bucket_total{bucket="gt_10"} 488
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 19606
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 19338
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 239
telemt_user_connections_total{user="hello"} 798236
telemt_user_connections_current{user="hello"} 650
telemt_user_octets_from_client{user="hello"} 9290477200 (8.65 GB)
telemt_user_octets_to_client{user="hello"} 234034932696 (217.96 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 88534.9 (24h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1101454
telemt_connections_bad_total 6936
telemt_handshake_timeouts_total 11195
telemt_upstream_connect_attempt_total 24017
telemt_upstream_connect_success_total 23911
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 24017
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12218
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11494
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 194
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 1908
telemt_me_reconnect_attempts_total 23427
telemt_me_reconnect_success_total 19342
telemt_me_reader_eof_total 20393
telemt_me_idle_close_by_peer_total 20393
telemt_me_route_drop_no_conn_total 392126
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1001117
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3851
telemt_desync_full_logged_total 1410
telemt_desync_suppressed_total 2441
telemt_desync_frames_bucket_total{bucket="1_2"} 1339
telemt_desync_frames_bucket_total{bucket="3_10"} 1449
telemt_desync_frames_bucket_total{bucket="gt_10"} 1063
telemt_pool_swap_total 59
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19719
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 19342
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 377
telemt_user_connections_total{user="hello"} 1000833
telemt_user_connections_current{user="hello"} 719
telemt_user_octets_from_client{user="hello"} 14329425307 (13.35 GB)
telemt_user_octets_to_client{user="hello"} 351715659554 (327.56 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 104
```