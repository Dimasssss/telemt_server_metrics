# Server Metrics 2026-03-14 20:54:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 27433.5 (7h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1031437
telemt_connections_bad_total 42343
telemt_handshake_timeouts_total 14665
telemt_upstream_connect_attempt_total 5017
telemt_upstream_connect_success_total 4994
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 5017
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2485
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2467
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 4382
telemt_me_reconnect_success_total 3574
telemt_me_reader_eof_total 3771
telemt_me_idle_close_by_peer_total 3771
telemt_me_route_drop_no_conn_total 394245
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 917194
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3096
telemt_desync_full_logged_total 883
telemt_desync_suppressed_total 2213
telemt_desync_frames_bucket_total{bucket="1_2"} 730
telemt_desync_frames_bucket_total{bucket="3_10"} 1142
telemt_desync_frames_bucket_total{bucket="gt_10"} 1224
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 3657
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 3565
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 917140
telemt_user_connections_current{user="hello"} 1361
telemt_user_octets_from_client{user="hello"} 16336101720 (15.21 GB)
telemt_user_octets_to_client{user="hello"} 309635080360 (288.37 GB)
telemt_user_unique_ips_current{user="hello"} 405
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 27438.7 (7h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 405292
telemt_connections_bad_total 30625
telemt_handshake_timeouts_total 12553
telemt_upstream_connect_attempt_total 5919
telemt_upstream_connect_success_total 5859
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 5919
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3038
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2708
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 478
telemt_me_reconnect_attempts_total 5238
telemt_me_reconnect_success_total 4440
telemt_me_reader_eof_total 4642
telemt_me_idle_close_by_peer_total 4642
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 119214
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 339052
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1661
telemt_desync_full_logged_total 439
telemt_desync_suppressed_total 1222
telemt_desync_frames_bucket_total{bucket="1_2"} 686
telemt_desync_frames_bucket_total{bucket="3_10"} 577
telemt_desync_frames_bucket_total{bucket="gt_10"} 398
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4557
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 4417
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 338997
telemt_user_connections_current{user="hello"} 447
telemt_user_octets_from_client{user="hello"} 4998076268 (4.65 GB)
telemt_user_octets_to_client{user="hello"} 118320039712 (110.19 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 27301.6 (7h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 881222
telemt_connections_bad_total 3648
telemt_handshake_timeouts_total 217196
telemt_upstream_connect_attempt_total 5311
telemt_upstream_connect_success_total 5294
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 5311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2729
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2551
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 7801
telemt_me_reconnect_success_total 3888
telemt_me_reader_eof_total 4170
telemt_me_idle_close_by_peer_total 4170
telemt_me_route_drop_no_conn_total 198023
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 562693
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2097
telemt_desync_full_logged_total 809
telemt_desync_suppressed_total 1288
telemt_desync_frames_bucket_total{bucket="1_2"} 298
telemt_desync_frames_bucket_total{bucket="3_10"} 735
telemt_desync_frames_bucket_total{bucket="gt_10"} 1064
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 4053
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3855
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 562521
telemt_user_connections_current{user="hello"} 648
telemt_user_octets_from_client{user="hello"} 8417206492 (7.84 GB)
telemt_user_octets_to_client{user="hello"} 208999782524 (194.65 GB)
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 27156.2 (7h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 468966
telemt_connections_bad_total 99679
telemt_handshake_timeouts_total 54457
telemt_upstream_connect_attempt_total 6264
telemt_upstream_connect_success_total 6263
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6264
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3025
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 213
telemt_me_reconnect_attempts_total 5787
telemt_me_reconnect_success_total 4865
telemt_me_reader_eof_total 5102
telemt_me_idle_close_by_peer_total 5102
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 108045
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 306853
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 694
telemt_desync_full_logged_total 243
telemt_desync_suppressed_total 451
telemt_desync_frames_bucket_total{bucket="1_2"} 240
telemt_desync_frames_bucket_total{bucket="3_10"} 229
telemt_desync_frames_bucket_total{bucket="gt_10"} 225
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 4952
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4853
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 306768
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 4300783248 (4.01 GB)
telemt_user_octets_to_client{user="hello"} 94888688168 (88.37 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 27451.5 (7h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 392627
telemt_connections_bad_total 1391
telemt_handshake_timeouts_total 3954
telemt_upstream_connect_attempt_total 5848
telemt_upstream_connect_success_total 5733
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 5848
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2799
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2886
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 141
telemt_me_reconnect_attempts_total 5010
telemt_me_reconnect_success_total 4334
telemt_me_reader_eof_total 4575
telemt_me_idle_close_by_peer_total 4575
telemt_me_route_drop_no_conn_total 123955
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 364319
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 939
telemt_desync_full_logged_total 335
telemt_desync_suppressed_total 604
telemt_desync_frames_bucket_total{bucket="1_2"} 309
telemt_desync_frames_bucket_total{bucket="3_10"} 290
telemt_desync_frames_bucket_total{bucket="gt_10"} 340
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4433
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 4316
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 364284
telemt_user_connections_current{user="hello"} 452
telemt_user_octets_from_client{user="hello"} 5865079212 (5.46 GB)
telemt_user_octets_to_client{user="hello"} 152890007652 (142.39 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 70
```