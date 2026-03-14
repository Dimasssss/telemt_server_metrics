# Server Metrics 2026-03-14 21:30:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 29579.9 (8h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1078727
telemt_connections_bad_total 42705
telemt_handshake_timeouts_total 14823
telemt_upstream_connect_attempt_total 5368
telemt_upstream_connect_success_total 5345
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 5368
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2675
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2626
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 4647
telemt_me_reconnect_success_total 3839
telemt_me_reader_eof_total 4051
telemt_me_idle_close_by_peer_total 4051
telemt_me_route_drop_no_conn_total 411620
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 961015
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3209
telemt_desync_full_logged_total 935
telemt_desync_suppressed_total 2274
telemt_desync_frames_bucket_total{bucket="1_2"} 757
telemt_desync_frames_bucket_total{bucket="3_10"} 1206
telemt_desync_frames_bucket_total{bucket="gt_10"} 1246
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 3925
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 3830
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 960985
telemt_user_connections_current{user="hello"} 1114
telemt_user_octets_from_client{user="hello"} 17075441472 (15.90 GB)
telemt_user_octets_to_client{user="hello"} 323334476532 (301.13 GB)
telemt_user_unique_ips_current{user="hello"} 357
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 29585.2 (8h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 425600
telemt_connections_bad_total 32607
telemt_handshake_timeouts_total 13122
telemt_upstream_connect_attempt_total 6316
telemt_upstream_connect_success_total 6254
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 6316
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2872
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 484
telemt_me_reconnect_attempts_total 5547
telemt_me_reconnect_success_total 4748
telemt_me_reader_eof_total 4969
telemt_me_idle_close_by_peer_total 4969
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 124519
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 356103
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1772
telemt_desync_full_logged_total 463
telemt_desync_suppressed_total 1309
telemt_desync_frames_bucket_total{bucket="1_2"} 723
telemt_desync_frames_bucket_total{bucket="3_10"} 616
telemt_desync_frames_bucket_total{bucket="gt_10"} 433
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4870
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 4725
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 356047
telemt_user_connections_current{user="hello"} 413
telemt_user_octets_from_client{user="hello"} 5636819600 (5.25 GB)
telemt_user_octets_to_client{user="hello"} 123433489188 (114.96 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 29448.1 (8h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 927045
telemt_connections_bad_total 3904
telemt_handshake_timeouts_total 234298
telemt_upstream_connect_attempt_total 5698
telemt_upstream_connect_success_total 5681
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 5698
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2746
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 117
telemt_me_reconnect_attempts_total 8102
telemt_me_reconnect_success_total 4188
telemt_me_reader_eof_total 4489
telemt_me_idle_close_by_peer_total 4489
telemt_me_route_drop_no_conn_total 206235
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 590769
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2213
telemt_desync_full_logged_total 844
telemt_desync_suppressed_total 1369
telemt_desync_frames_bucket_total{bucket="1_2"} 336
telemt_desync_frames_bucket_total{bucket="3_10"} 773
telemt_desync_frames_bucket_total{bucket="gt_10"} 1104
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 4359
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 4155
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 590592
telemt_user_connections_current{user="hello"} 680
telemt_user_octets_from_client{user="hello"} 9073161048 (8.45 GB)
telemt_user_octets_to_client{user="hello"} 220168481404 (205.05 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 29302.5 (8h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 489937
telemt_connections_bad_total 101367
telemt_handshake_timeouts_total 55440
telemt_upstream_connect_attempt_total 6747
telemt_upstream_connect_success_total 6746
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3278
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 218
telemt_me_reconnect_attempts_total 6183
telemt_me_reconnect_success_total 5260
telemt_me_reader_eof_total 5523
telemt_me_idle_close_by_peer_total 5523
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 113705
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 324925
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 705
telemt_desync_full_logged_total 247
telemt_desync_suppressed_total 458
telemt_desync_frames_bucket_total{bucket="1_2"} 243
telemt_desync_frames_bucket_total{bucket="3_10"} 233
telemt_desync_frames_bucket_total{bucket="gt_10"} 229
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5348
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5248
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 324839
telemt_user_connections_current{user="hello"} 392
telemt_user_octets_from_client{user="hello"} 4557798560 (4.24 GB)
telemt_user_octets_to_client{user="hello"} 99825758220 (92.97 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 29597.9 (8h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 410833
telemt_connections_bad_total 1402
telemt_handshake_timeouts_total 4060
telemt_upstream_connect_attempt_total 6247
telemt_upstream_connect_success_total 6123
telemt_upstream_connect_fail_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 6247
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2976
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3099
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 124
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 5314
telemt_me_reconnect_success_total 4635
telemt_me_reader_eof_total 4896
telemt_me_idle_close_by_peer_total 4896
telemt_me_route_drop_no_conn_total 129053
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 381486
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1105
telemt_desync_full_logged_total 388
telemt_desync_suppressed_total 717
telemt_desync_frames_bucket_total{bucket="1_2"} 349
telemt_desync_frames_bucket_total{bucket="3_10"} 352
telemt_desync_frames_bucket_total{bucket="gt_10"} 404
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 4739
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 4617
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 381451
telemt_user_connections_current{user="hello"} 413
telemt_user_octets_from_client{user="hello"} 6011605128 (5.60 GB)
telemt_user_octets_to_client{user="hello"} 156474493652 (145.73 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 57
```