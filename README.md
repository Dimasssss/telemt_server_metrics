# Server Metrics 2026-03-12 14:55:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 32194.4 (8h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1150626
telemt_connections_bad_total 18908
telemt_handshake_timeouts_total 11955
telemt_upstream_connect_attempt_total 6350
telemt_upstream_connect_success_total 6316
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 6350
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3370
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2936
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 407
telemt_me_reconnect_attempts_total 8584
telemt_me_reconnect_success_total 4681
telemt_me_reader_eof_total 4998
telemt_me_idle_close_by_peer_total 4997
telemt_me_route_drop_no_conn_total 407691
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1083321
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5768
telemt_desync_full_logged_total 1450
telemt_desync_suppressed_total 4318
telemt_desync_frames_bucket_total{bucket="1_2"} 1478
telemt_desync_frames_bucket_total{bucket="3_10"} 2076
telemt_desync_frames_bucket_total{bucket="gt_10"} 2214
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 4857
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 4668
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 1083056
telemt_user_connections_current{user="hello"} 1596
telemt_user_octets_from_client{user="hello"} 17149057132 (15.97 GB)
telemt_user_octets_to_client{user="hello"} 316051918644 (294.35 GB)
telemt_user_unique_ips_current{user="hello"} 435
telemt_user_unique_ips_recent_window{user="hello"} 224
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 61814.8 (17h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 528123
telemt_connections_bad_total 5896
telemt_handshake_timeouts_total 26644
telemt_upstream_connect_attempt_total 14867
telemt_upstream_connect_success_total 14860
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 14867
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7365
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7479
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1176
telemt_me_reconnect_attempts_total 11658
telemt_me_reconnect_success_total 11593
telemt_me_reader_eof_total 12305
telemt_me_idle_close_by_peer_total 12305
telemt_me_route_drop_no_conn_total 153849
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 470574
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1798
telemt_desync_full_logged_total 567
telemt_desync_suppressed_total 1231
telemt_desync_frames_bucket_total{bucket="1_2"} 770
telemt_desync_frames_bucket_total{bucket="3_10"} 581
telemt_desync_frames_bucket_total{bucket="gt_10"} 447
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 11699
telemt_me_writer_restored_same_endpoint_total 11584
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 471073
telemt_user_connections_current{user="hello"} 545
telemt_user_octets_from_client{user="hello"} 7261242843 (6.76 GB)
telemt_user_octets_to_client{user="hello"} 165927163578 (154.53 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 61814.6 (17h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1132304
telemt_connections_bad_total 6059
telemt_handshake_timeouts_total 80485
telemt_upstream_connect_attempt_total 14837
telemt_upstream_connect_success_total 14832
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 14837
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8051
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6719
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 973
telemt_me_reconnect_attempts_total 12610
telemt_me_reconnect_success_total 11389
telemt_me_reader_eof_total 12020
telemt_me_idle_close_by_peer_total 12020
telemt_me_route_drop_no_conn_total 299218
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 823029
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3410
telemt_desync_full_logged_total 1049
telemt_desync_suppressed_total 2361
telemt_desync_frames_bucket_total{bucket="1_2"} 505
telemt_desync_frames_bucket_total{bucket="3_10"} 1239
telemt_desync_frames_bucket_total{bucket="gt_10"} 1666
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 11468
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 11348
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 823217
telemt_user_connections_current{user="hello"} 887
telemt_user_octets_from_client{user="hello"} 10872720620 (10.13 GB)
telemt_user_octets_to_client{user="hello"} 260273689557 (242.40 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 261
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 61815.2 (17h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 666843
telemt_connections_bad_total 7695
telemt_handshake_timeouts_total 56945
telemt_upstream_connect_attempt_total 16468
telemt_upstream_connect_success_total 16400
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 16468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9305
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7082
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 1350
telemt_me_reconnect_attempts_total 15832
telemt_me_reconnect_success_total 13315
telemt_me_reader_eof_total 14128
telemt_me_idle_close_by_peer_total 14128
telemt_me_route_drop_no_conn_total 224681
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 568952
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1138
telemt_desync_full_logged_total 392
telemt_desync_suppressed_total 746
telemt_desync_frames_bucket_total{bucket="1_2"} 314
telemt_desync_frames_bucket_total{bucket="3_10"} 461
telemt_desync_frames_bucket_total{bucket="gt_10"} 363
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 13494
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 13294
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 568453
telemt_user_connections_current{user="hello"} 635
telemt_user_octets_from_client{user="hello"} 6846388640 (6.38 GB)
telemt_user_octets_to_client{user="hello"} 228186877448 (212.52 GB)
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 61815.0 (17h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 750215
telemt_connections_bad_total 5777
telemt_handshake_timeouts_total 6022
telemt_upstream_connect_attempt_total 19338
telemt_upstream_connect_success_total 19104
telemt_upstream_connect_fail_total 234
telemt_upstream_connect_attempts_per_request{bucket="1"} 19338
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9301
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 234
telemt_me_keepalive_timeout_total 1079
telemt_me_reconnect_attempts_total 23249
telemt_me_reconnect_success_total 16019
telemt_me_reader_eof_total 16780
telemt_me_idle_close_by_peer_total 16780
telemt_me_seq_mismatch_total 27
telemt_me_route_drop_no_conn_total 260207
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 693773
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 31
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2785
telemt_desync_full_logged_total 938
telemt_desync_suppressed_total 1847
telemt_desync_frames_bucket_total{bucket="1_2"} 791
telemt_desync_frames_bucket_total{bucket="3_10"} 963
telemt_desync_frames_bucket_total{bucket="gt_10"} 1031
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 16408
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 15985
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 389
telemt_user_connections_total{user="hello"} 693673
telemt_user_connections_current{user="hello"} 797
telemt_user_octets_from_client{user="hello"} 8166447088 (7.61 GB)
telemt_user_octets_to_client{user="hello"} 192110173516 (178.92 GB)
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 118
```