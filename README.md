# Server Metrics 2026-03-14 21:51:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 30806.8 (8h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1101930
telemt_connections_bad_total 42834
telemt_handshake_timeouts_total 14875
telemt_upstream_connect_attempt_total 5631
telemt_upstream_connect_success_total 5608
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 5631
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2825
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2739
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 4824
telemt_me_reconnect_success_total 4015
telemt_me_reader_eof_total 4242
telemt_me_idle_close_by_peer_total 4242
telemt_me_route_drop_no_conn_total 420327
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 982849
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3244
telemt_desync_full_logged_total 950
telemt_desync_suppressed_total 2294
telemt_desync_frames_bucket_total{bucket="1_2"} 765
telemt_desync_frames_bucket_total{bucket="3_10"} 1227
telemt_desync_frames_bucket_total{bucket="gt_10"} 1252
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 4105
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 4006
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 982817
telemt_user_connections_current{user="hello"} 985
telemt_user_octets_from_client{user="hello"} 18156810192 (16.91 GB)
telemt_user_octets_to_client{user="hello"} 331512156028 (308.74 GB)
telemt_user_unique_ips_current{user="hello"} 313
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 30811.9 (8h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 435449
telemt_connections_bad_total 33745
telemt_handshake_timeouts_total 13381
telemt_upstream_connect_attempt_total 6604
telemt_upstream_connect_success_total 6540
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 6604
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3438
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2981
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 486
telemt_me_reconnect_attempts_total 5747
telemt_me_reconnect_success_total 4944
telemt_me_reader_eof_total 5185
telemt_me_idle_close_by_peer_total 5185
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 127128
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 364287
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1817
telemt_desync_full_logged_total 477
telemt_desync_suppressed_total 1340
telemt_desync_frames_bucket_total{bucket="1_2"} 739
telemt_desync_frames_bucket_total{bucket="3_10"} 633
telemt_desync_frames_bucket_total{bucket="gt_10"} 445
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5072
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 4921
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 128
telemt_user_connections_total{user="hello"} 364231
telemt_user_connections_current{user="hello"} 333
telemt_user_octets_from_client{user="hello"} 5726262756 (5.33 GB)
telemt_user_octets_to_client{user="hello"} 128333814212 (119.52 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 30674.8 (8h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 953231
telemt_connections_bad_total 3956
telemt_handshake_timeouts_total 244311
telemt_upstream_connect_attempt_total 5981
telemt_upstream_connect_success_total 5963
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 5981
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2878
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 8311
telemt_me_reconnect_success_total 4396
telemt_me_reader_eof_total 4705
telemt_me_idle_close_by_peer_total 4705
telemt_me_route_drop_no_conn_total 209820
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 604185
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2234
telemt_desync_full_logged_total 854
telemt_desync_suppressed_total 1380
telemt_desync_frames_bucket_total{bucket="1_2"} 342
telemt_desync_frames_bucket_total{bucket="3_10"} 780
telemt_desync_frames_bucket_total{bucket="gt_10"} 1112
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 4568
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 4363
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 604007
telemt_user_connections_current{user="hello"} 564
telemt_user_octets_from_client{user="hello"} 9621150692 (8.96 GB)
telemt_user_octets_to_client{user="hello"} 224222996668 (208.82 GB)
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 30529.5 (8h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 500811
telemt_connections_bad_total 102370
telemt_handshake_timeouts_total 56201
telemt_upstream_connect_attempt_total 6967
telemt_upstream_connect_success_total 6966
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6967
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3504
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3378
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 221
telemt_me_reconnect_attempts_total 6360
telemt_me_reconnect_success_total 5436
telemt_me_reader_eof_total 5710
telemt_me_idle_close_by_peer_total 5710
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 116897
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 333941
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 730
telemt_desync_full_logged_total 256
telemt_desync_suppressed_total 474
telemt_desync_frames_bucket_total{bucket="1_2"} 245
telemt_desync_frames_bucket_total{bucket="3_10"} 247
telemt_desync_frames_bucket_total{bucket="gt_10"} 238
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 5528
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5424
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 333855
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 4618951896 (4.30 GB)
telemt_user_octets_to_client{user="hello"} 103313907584 (96.22 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 30825.0 (8h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 420117
telemt_connections_bad_total 1406
telemt_handshake_timeouts_total 4144
telemt_upstream_connect_attempt_total 6526
telemt_upstream_connect_success_total 6398
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 6526
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3242
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 153
telemt_me_reconnect_attempts_total 5503
telemt_me_reconnect_success_total 4823
telemt_me_reader_eof_total 5102
telemt_me_idle_close_by_peer_total 5102
telemt_me_route_drop_no_conn_total 131489
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 390215
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1158
telemt_desync_full_logged_total 408
telemt_desync_suppressed_total 750
telemt_desync_frames_bucket_total{bucket="1_2"} 356
telemt_desync_frames_bucket_total{bucket="3_10"} 370
telemt_desync_frames_bucket_total{bucket="gt_10"} 432
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 4929
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 4805
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 390180
telemt_user_connections_current{user="hello"} 519
telemt_user_octets_from_client{user="hello"} 6150129176 (5.73 GB)
telemt_user_octets_to_client{user="hello"} 161682317060 (150.58 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 49
```