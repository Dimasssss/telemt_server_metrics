# Server Metrics 2026-03-11 00:05:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 34714.3 (9h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 776447
telemt_connections_bad_total 9287
telemt_handshake_timeouts_total 8766
telemt_upstream_connect_attempt_total 7547
telemt_upstream_connect_success_total 7538
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 7547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3762
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3718
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 467
telemt_me_reconnect_attempts_total 17394
telemt_me_reconnect_success_total 5731
telemt_me_reader_eof_total 6293
telemt_me_idle_close_by_peer_total 6293
telemt_me_route_drop_no_conn_total 320740
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 734905
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3540
telemt_desync_full_logged_total 989
telemt_desync_suppressed_total 2551
telemt_desync_frames_bucket_total{bucket="1_2"} 1025
telemt_desync_frames_bucket_total{bucket="3_10"} 1319
telemt_desync_frames_bucket_total{bucket="gt_10"} 1196
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 6142
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 5725
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 411
telemt_user_connections_total{user="hello"} 734690
telemt_user_connections_current{user="hello"} 376
telemt_user_octets_from_client{user="hello"} 10177795636 (9.48 GB)
telemt_user_octets_to_client{user="hello"} 218695108052 (203.68 GB)
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 34771.0 (9h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 335509
telemt_connections_bad_total 2383
telemt_handshake_timeouts_total 17623
telemt_upstream_connect_attempt_total 14458
telemt_upstream_connect_success_total 11580
telemt_upstream_connect_fail_total 2878
telemt_upstream_connect_attempts_per_request{bucket="1"} 14458
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4970
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4370
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2878
telemt_me_keepalive_timeout_total 1703
telemt_me_reconnect_attempts_total 7670
telemt_me_reconnect_success_total 6858
telemt_me_reader_eof_total 7227
telemt_me_idle_close_by_peer_total 7225
telemt_me_route_drop_no_conn_total 171169
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 285079
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1733
telemt_desync_full_logged_total 483
telemt_desync_suppressed_total 1250
telemt_desync_frames_bucket_total{bucket="1_2"} 527
telemt_desync_frames_bucket_total{bucket="3_10"} 613
telemt_desync_frames_bucket_total{bucket="gt_10"} 593
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 6955
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 6837
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 287348
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 2785971314 (2.59 GB)
telemt_user_octets_to_client{user="hello"} 69372119936 (64.61 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 34770.6 (9h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 557556
telemt_connections_bad_total 3855
telemt_handshake_timeouts_total 34007
telemt_upstream_connect_attempt_total 9484
telemt_upstream_connect_success_total 9350
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 9484
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5302
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3984
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_timeout_total 498
telemt_me_reconnect_attempts_total 17561
telemt_me_reconnect_success_total 6502
telemt_me_reader_eof_total 7102
telemt_me_idle_close_by_peer_total 7102
telemt_me_route_drop_no_conn_total 192351
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 491214
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1521
telemt_desync_full_logged_total 434
telemt_desync_suppressed_total 1087
telemt_desync_frames_bucket_total{bucket="1_2"} 343
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 655
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 6943
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 6491
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 441
telemt_user_connections_total{user="hello"} 492139
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 6772472365 (6.31 GB)
telemt_user_octets_to_client{user="hello"} 152654768421 (142.17 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 34771.2 (9h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 403307
telemt_connections_bad_total 33181
telemt_handshake_timeouts_total 37340
telemt_upstream_connect_attempt_total 9779
telemt_upstream_connect_success_total 9779
telemt_upstream_connect_attempts_per_request{bucket="1"} 9779
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5521
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4257
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 393
telemt_me_reconnect_attempts_total 9034
telemt_me_reconnect_success_total 8004
telemt_me_reader_eof_total 8440
telemt_me_idle_close_by_peer_total 8440
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 125629
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 319814
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 697
telemt_desync_full_logged_total 282
telemt_desync_suppressed_total 415
telemt_desync_frames_bucket_total{bucket="1_2"} 269
telemt_desync_frames_bucket_total{bucket="3_10"} 245
telemt_desync_frames_bucket_total{bucket="gt_10"} 183
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 8117
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 7989
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 319489
telemt_user_connections_current{user="hello"} 176
telemt_user_octets_from_client{user="hello"} 4118848168 (3.84 GB)
telemt_user_octets_to_client{user="hello"} 89688256492 (83.53 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 34770.6 (9h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 426828
telemt_connections_bad_total 3332
telemt_handshake_timeouts_total 2711
telemt_upstream_connect_attempt_total 10567
telemt_upstream_connect_success_total 10527
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 10567
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4918
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 498
telemt_me_reconnect_attempts_total 12482
telemt_me_reconnect_success_total 8719
telemt_me_reader_eof_total 9161
telemt_me_idle_close_by_peer_total 9161
telemt_me_route_drop_no_conn_total 144294
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 395011
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2248
telemt_desync_full_logged_total 866
telemt_desync_suppressed_total 1382
telemt_desync_frames_bucket_total{bucket="1_2"} 828
telemt_desync_frames_bucket_total{bucket="3_10"} 964
telemt_desync_frames_bucket_total{bucket="gt_10"} 456
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 8950
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 8719
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 231
telemt_user_connections_total{user="hello"} 394772
telemt_user_connections_current{user="hello"} 252
telemt_user_octets_from_client{user="hello"} 8296452944 (7.73 GB)
telemt_user_octets_to_client{user="hello"} 144650376592 (134.72 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 41
```