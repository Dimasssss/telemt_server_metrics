# Server Metrics 2026-03-11 01:21:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 39285.6 (10h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 810286
telemt_connections_bad_total 9523
telemt_handshake_timeouts_total 9641
telemt_upstream_connect_attempt_total 8551
telemt_upstream_connect_success_total 8542
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 8551
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4270
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4213
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 482
telemt_me_reconnect_attempts_total 18182
telemt_me_reconnect_success_total 6516
telemt_me_reader_eof_total 7134
telemt_me_idle_close_by_peer_total 7134
telemt_me_route_drop_no_conn_total 331087
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 767150
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3597
telemt_desync_full_logged_total 1012
telemt_desync_suppressed_total 2585
telemt_desync_frames_bucket_total{bucket="1_2"} 1053
telemt_desync_frames_bucket_total{bucket="3_10"} 1340
telemt_desync_frames_bucket_total{bucket="gt_10"} 1204
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 6934
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 6510
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 418
telemt_user_connections_total{user="hello"} 766911
telemt_user_connections_current{user="hello"} 463
telemt_user_octets_from_client{user="hello"} 10579498100 (9.85 GB)
telemt_user_octets_to_client{user="hello"} 233518361516 (217.48 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 39342.3 (10h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 348537
telemt_connections_bad_total 2405
telemt_handshake_timeouts_total 17832
telemt_upstream_connect_attempt_total 15755
telemt_upstream_connect_success_total 12870
telemt_upstream_connect_fail_total 2885
telemt_upstream_connect_attempts_per_request{bucket="1"} 15755
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5602
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5028
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2885
telemt_me_keepalive_timeout_total 1716
telemt_me_reconnect_attempts_total 8743
telemt_me_reconnect_success_total 7927
telemt_me_reader_eof_total 8372
telemt_me_idle_close_by_peer_total 8370
telemt_me_route_drop_no_conn_total 174090
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 297613
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1780
telemt_desync_full_logged_total 510
telemt_desync_suppressed_total 1270
telemt_desync_frames_bucket_total{bucket="1_2"} 545
telemt_desync_frames_bucket_total{bucket="3_10"} 633
telemt_desync_frames_bucket_total{bucket="gt_10"} 602
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 8035
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 7906
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 299882
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 2860586454 (2.66 GB)
telemt_user_octets_to_client{user="hello"} 71156021716 (66.27 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 39342.1 (10h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 579656
telemt_connections_bad_total 4181
telemt_handshake_timeouts_total 34241
telemt_upstream_connect_attempt_total 10726
telemt_upstream_connect_success_total 10579
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 10726
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5929
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4584
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 516
telemt_me_reconnect_attempts_total 18572
telemt_me_reconnect_success_total 7509
telemt_me_reader_eof_total 8182
telemt_me_idle_close_by_peer_total 8182
telemt_me_route_drop_no_conn_total 198312
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 512606
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1522
telemt_desync_full_logged_total 435
telemt_desync_suppressed_total 1087
telemt_desync_frames_bucket_total{bucket="1_2"} 344
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 655
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 7956
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 7498
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 447
telemt_user_connections_total{user="hello"} 513521
telemt_user_connections_current{user="hello"} 219
telemt_user_octets_from_client{user="hello"} 6913169681 (6.44 GB)
telemt_user_octets_to_client{user="hello"} 155958006869 (145.25 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 39342.5 (10h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 428266
telemt_connections_bad_total 37345
telemt_handshake_timeouts_total 40673
telemt_upstream_connect_attempt_total 11316
telemt_upstream_connect_success_total 11316
telemt_upstream_connect_attempts_per_request{bucket="1"} 11316
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6376
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4938
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 419
telemt_me_reconnect_attempts_total 10356
telemt_me_reconnect_success_total 9322
telemt_me_reader_eof_total 9862
telemt_me_idle_close_by_peer_total 9862
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 130233
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 337160
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 726
telemt_desync_full_logged_total 290
telemt_desync_suppressed_total 436
telemt_desync_frames_bucket_total{bucket="1_2"} 278
telemt_desync_frames_bucket_total{bucket="3_10"} 252
telemt_desync_frames_bucket_total{bucket="gt_10"} 196
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 9439
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 9304
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 336836
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 4236659416 (3.95 GB)
telemt_user_octets_to_client{user="hello"} 91838219368 (85.53 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 39342.1 (10h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 452477
telemt_connections_bad_total 5160
telemt_handshake_timeouts_total 2930
telemt_upstream_connect_attempt_total 11798
telemt_upstream_connect_success_total 11748
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 11798
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5552
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 512
telemt_me_reconnect_attempts_total 13486
telemt_me_reconnect_success_total 9718
telemt_me_reader_eof_total 10227
telemt_me_idle_close_by_peer_total 10227
telemt_me_route_drop_no_conn_total 149386
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 415003
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2284
telemt_desync_full_logged_total 885
telemt_desync_suppressed_total 1399
telemt_desync_frames_bucket_total{bucket="1_2"} 844
telemt_desync_frames_bucket_total{bucket="3_10"} 972
telemt_desync_frames_bucket_total{bucket="gt_10"} 468
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 9961
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 9718
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 414709
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 8393930964 (7.82 GB)
telemt_user_octets_to_client{user="hello"} 147831834668 (137.68 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 28
```