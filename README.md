# Server Metrics 2026-03-14 21:45:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 30500.3 (8h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1096590
telemt_connections_bad_total 42808
telemt_handshake_timeouts_total 14850
telemt_upstream_connect_attempt_total 5543
telemt_upstream_connect_success_total 5520
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 5543
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2698
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 117
telemt_me_reconnect_attempts_total 4779
telemt_me_reconnect_success_total 3970
telemt_me_reader_eof_total 4190
telemt_me_idle_close_by_peer_total 4190
telemt_me_route_drop_no_conn_total 418121
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 977874
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3231
telemt_desync_full_logged_total 945
telemt_desync_suppressed_total 2286
telemt_desync_frames_bucket_total{bucket="1_2"} 764
telemt_desync_frames_bucket_total{bucket="3_10"} 1219
telemt_desync_frames_bucket_total{bucket="gt_10"} 1248
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 4060
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 3961
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 977843
telemt_user_connections_current{user="hello"} 1038
telemt_user_octets_from_client{user="hello"} 17691145036 (16.48 GB)
telemt_user_octets_to_client{user="hello"} 330040351576 (307.37 GB)
telemt_user_unique_ips_current{user="hello"} 338
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 30505.4 (8h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 433269
telemt_connections_bad_total 33446
telemt_handshake_timeouts_total 13334
telemt_upstream_connect_attempt_total 6502
telemt_upstream_connect_success_total 6440
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 6502
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3381
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2941
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 105
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 486
telemt_me_reconnect_attempts_total 5690
telemt_me_reconnect_success_total 4889
telemt_me_reader_eof_total 5119
telemt_me_idle_close_by_peer_total 5119
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 126289
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 362513
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1804
telemt_desync_full_logged_total 475
telemt_desync_suppressed_total 1329
telemt_desync_frames_bucket_total{bucket="1_2"} 737
telemt_desync_frames_bucket_total{bucket="3_10"} 628
telemt_desync_frames_bucket_total{bucket="gt_10"} 439
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 5014
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 4866
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 362457
telemt_user_connections_current{user="hello"} 341
telemt_user_octets_from_client{user="hello"} 5714991960 (5.32 GB)
telemt_user_octets_to_client{user="hello"} 127833935400 (119.05 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 30368.4 (8h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 943496
telemt_connections_bad_total 3956
telemt_handshake_timeouts_total 239177
telemt_upstream_connect_attempt_total 5909
telemt_upstream_connect_success_total 5891
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 5909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3031
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2844
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 8268
telemt_me_reconnect_success_total 4353
telemt_me_reader_eof_total 4662
telemt_me_idle_close_by_peer_total 4662
telemt_me_route_drop_no_conn_total 208947
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 601095
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2233
telemt_desync_full_logged_total 853
telemt_desync_suppressed_total 1380
telemt_desync_frames_bucket_total{bucket="1_2"} 341
telemt_desync_frames_bucket_total{bucket="3_10"} 780
telemt_desync_frames_bucket_total{bucket="gt_10"} 1112
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 4525
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 4320
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 600917
telemt_user_connections_current{user="hello"} 597
telemt_user_octets_from_client{user="hello"} 9256551188 (8.62 GB)
telemt_user_octets_to_client{user="hello"} 223718349552 (208.35 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 30222.8 (8h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 498283
telemt_connections_bad_total 102072
telemt_handshake_timeouts_total 55882
telemt_upstream_connect_attempt_total 6929
telemt_upstream_connect_success_total 6928
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6929
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3360
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 220
telemt_me_reconnect_attempts_total 6322
telemt_me_reconnect_success_total 5398
telemt_me_reader_eof_total 5672
telemt_me_idle_close_by_peer_total 5672
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 116092
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 332010
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 719
telemt_desync_full_logged_total 251
telemt_desync_suppressed_total 468
telemt_desync_frames_bucket_total{bucket="1_2"} 244
telemt_desync_frames_bucket_total{bucket="3_10"} 240
telemt_desync_frames_bucket_total{bucket="gt_10"} 235
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 5490
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5386
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 331924
telemt_user_connections_current{user="hello"} 312
telemt_user_octets_from_client{user="hello"} 4605819588 (4.29 GB)
telemt_user_octets_to_client{user="hello"} 102511083776 (95.47 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 30518.2 (8h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 417622
telemt_connections_bad_total 1406
telemt_handshake_timeouts_total 4108
telemt_upstream_connect_attempt_total 6430
telemt_upstream_connect_success_total 6305
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 6430
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3062
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3195
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_timeout_total 153
telemt_me_reconnect_attempts_total 5453
telemt_me_reconnect_success_total 4774
telemt_me_reader_eof_total 5045
telemt_me_idle_close_by_peer_total 5045
telemt_me_route_drop_no_conn_total 130808
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 387960
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1141
telemt_desync_full_logged_total 402
telemt_desync_suppressed_total 739
telemt_desync_frames_bucket_total{bucket="1_2"} 355
telemt_desync_frames_bucket_total{bucket="3_10"} 362
telemt_desync_frames_bucket_total{bucket="gt_10"} 424
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 4879
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 4756
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 105
telemt_user_connections_total{user="hello"} 387925
telemt_user_connections_current{user="hello"} 488
telemt_user_octets_from_client{user="hello"} 6123888356 (5.70 GB)
telemt_user_octets_to_client{user="hello"} 159098363228 (148.17 GB)
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 47
```