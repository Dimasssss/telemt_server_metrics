# Server Metrics 2026-03-15 07:11:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 32199.6 (8h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 555043
telemt_connections_bad_total 14902
telemt_handshake_timeouts_total 3807
telemt_upstream_connect_attempt_total 6739
telemt_upstream_connect_success_total 6713
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 6739
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3541
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3164
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 5137
telemt_me_reconnect_success_total 5111
telemt_me_reader_eof_total 5405
telemt_me_idle_close_by_peer_total 5405
telemt_me_route_drop_no_conn_total 170881
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 469103
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1239
telemt_desync_full_logged_total 394
telemt_desync_suppressed_total 845
telemt_desync_frames_bucket_total{bucket="1_2"} 254
telemt_desync_frames_bucket_total{bucket="3_10"} 454
telemt_desync_frames_bucket_total{bucket="gt_10"} 531
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 5175
telemt_me_writer_restored_same_endpoint_total 5100
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 469111
telemt_user_connections_current{user="hello"} 1681
telemt_user_octets_from_client{user="hello"} 5634565468 (5.25 GB)
telemt_user_octets_to_client{user="hello"} 166414675176 (154.99 GB)
telemt_user_unique_ips_current{user="hello"} 488
telemt_user_unique_ips_recent_window{user="hello"} 203
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 32200.6 (8h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 200938
telemt_connections_bad_total 18331
telemt_handshake_timeouts_total 6245
telemt_upstream_connect_attempt_total 8995
telemt_upstream_connect_success_total 8949
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 8995
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4853
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4031
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 7067
telemt_me_reconnect_success_total 7026
telemt_me_reader_eof_total 7436
telemt_me_idle_close_by_peer_total 7436
telemt_me_route_drop_no_conn_total 52119
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168805
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 578
telemt_desync_full_logged_total 199
telemt_desync_suppressed_total 379
telemt_desync_frames_bucket_total{bucket="1_2"} 152
telemt_desync_frames_bucket_total{bucket="3_10"} 234
telemt_desync_frames_bucket_total{bucket="gt_10"} 192
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 7059
telemt_me_writer_restored_same_endpoint_total 7018
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 169093
telemt_user_connections_current{user="hello"} 601
telemt_user_octets_from_client{user="hello"} 2685717927 (2.50 GB)
telemt_user_octets_to_client{user="hello"} 62712721200 (58.41 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 32200.6 (8h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 371673
telemt_connections_bad_total 10657
telemt_handshake_timeouts_total 35555
telemt_upstream_connect_attempt_total 7339
telemt_upstream_connect_success_total 7307
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 7339
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3871
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3410
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 5727
telemt_me_reconnect_success_total 5696
telemt_me_reader_eof_total 6031
telemt_me_idle_close_by_peer_total 6031
telemt_me_route_drop_no_conn_total 95562
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 304899
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 584
telemt_desync_full_logged_total 240
telemt_desync_suppressed_total 344
telemt_desync_frames_bucket_total{bucket="1_2"} 131
telemt_desync_frames_bucket_total{bucket="3_10"} 207
telemt_desync_frames_bucket_total{bucket="gt_10"} 246
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 5760
telemt_me_writer_restored_same_endpoint_total 5677
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 304708
telemt_user_connections_current{user="hello"} 906
telemt_user_octets_from_client{user="hello"} 4746420776 (4.42 GB)
telemt_user_octets_to_client{user="hello"} 127195734592 (118.46 GB)
telemt_user_unique_ips_current{user="hello"} 293
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 32200.4 (8h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 248666
telemt_connections_bad_total 44242
telemt_handshake_timeouts_total 16247
telemt_upstream_connect_attempt_total 10650
telemt_upstream_connect_success_total 10404
telemt_upstream_connect_fail_total 246
telemt_upstream_connect_attempts_per_request{bucket="1"} 10650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4923
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5478
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 246
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 20074
telemt_me_reconnect_success_total 8798
telemt_me_reader_eof_total 9425
telemt_me_idle_close_by_peer_total 9425
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 59884
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 182404
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 296
telemt_desync_full_logged_total 81
telemt_desync_suppressed_total 215
telemt_desync_frames_bucket_total{bucket="1_2"} 83
telemt_desync_frames_bucket_total{bucket="3_10"} 125
telemt_desync_frames_bucket_total{bucket="gt_10"} 88
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 9223
telemt_me_refill_failed_total 351
telemt_me_writer_restored_same_endpoint_total 8772
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 425
telemt_user_connections_total{user="hello"} 182407
telemt_user_connections_current{user="hello"} 433
telemt_user_octets_from_client{user="hello"} 1539090128 (1.43 GB)
telemt_user_octets_to_client{user="hello"} 62928201720 (58.61 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 32201.2 (8h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 186823
telemt_connections_bad_total 264
telemt_handshake_timeouts_total 1795
telemt_upstream_connect_attempt_total 7165
telemt_upstream_connect_success_total 7137
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 7165
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3972
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_reconnect_attempts_total 5559
telemt_me_reconnect_success_total 5533
telemt_me_reader_eof_total 5907
telemt_me_idle_close_by_peer_total 5907
telemt_me_route_drop_no_conn_total 56880
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 175637
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 691
telemt_desync_full_logged_total 228
telemt_desync_suppressed_total 463
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 271
telemt_desync_frames_bucket_total{bucket="gt_10"} 206
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 5588
telemt_me_writer_restored_same_endpoint_total 5525
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 175644
telemt_user_connections_current{user="hello"} 628
telemt_user_octets_from_client{user="hello"} 1735770432 (1.62 GB)
telemt_user_octets_to_client{user="hello"} 66863315272 (62.27 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 100
```