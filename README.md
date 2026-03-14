# Server Metrics 2026-03-14 21:20:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 28966.8 (8h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1065551
telemt_connections_bad_total 42423
telemt_handshake_timeouts_total 14782
telemt_upstream_connect_attempt_total 5286
telemt_upstream_connect_success_total 5263
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 5286
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2629
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2590
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 4565
telemt_me_reconnect_success_total 3757
telemt_me_reader_eof_total 3964
telemt_me_idle_close_by_peer_total 3964
telemt_me_route_drop_no_conn_total 406807
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 948842
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3161
telemt_desync_full_logged_total 918
telemt_desync_suppressed_total 2243
telemt_desync_frames_bucket_total{bucket="1_2"} 748
telemt_desync_frames_bucket_total{bucket="3_10"} 1176
telemt_desync_frames_bucket_total{bucket="gt_10"} 1237
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 3842
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 3748
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 948814
telemt_user_connections_current{user="hello"} 1150
telemt_user_octets_from_client{user="hello"} 16864762068 (15.71 GB)
telemt_user_octets_to_client{user="hello"} 319007736676 (297.10 GB)
telemt_user_unique_ips_current{user="hello"} 364
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 28972.0 (8h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 420143
telemt_connections_bad_total 32029
telemt_handshake_timeouts_total 13020
telemt_upstream_connect_attempt_total 6217
telemt_upstream_connect_success_total 6155
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 6217
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2826
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 482
telemt_me_reconnect_attempts_total 5448
telemt_me_reconnect_success_total 4650
telemt_me_reader_eof_total 4866
telemt_me_idle_close_by_peer_total 4866
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 122794
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 351430
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1735
telemt_desync_full_logged_total 454
telemt_desync_suppressed_total 1281
telemt_desync_frames_bucket_total{bucket="1_2"} 715
telemt_desync_frames_bucket_total{bucket="3_10"} 599
telemt_desync_frames_bucket_total{bucket="gt_10"} 421
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4770
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 4627
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 120
telemt_user_connections_total{user="hello"} 351374
telemt_user_connections_current{user="hello"} 433
telemt_user_octets_from_client{user="hello"} 5559559412 (5.18 GB)
telemt_user_octets_to_client{user="hello"} 121640245292 (113.29 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 28834.9 (8h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 911431
telemt_connections_bad_total 3897
telemt_handshake_timeouts_total 226937
telemt_upstream_connect_attempt_total 5570
telemt_upstream_connect_success_total 5553
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 5570
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2853
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2686
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 8010
telemt_me_reconnect_success_total 4097
telemt_me_reader_eof_total 4389
telemt_me_idle_close_by_peer_total 4389
telemt_me_route_drop_no_conn_total 204476
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 583295
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2197
telemt_desync_full_logged_total 838
telemt_desync_suppressed_total 1359
telemt_desync_frames_bucket_total{bucket="1_2"} 332
telemt_desync_frames_bucket_total{bucket="3_10"} 766
telemt_desync_frames_bucket_total{bucket="gt_10"} 1099
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 4265
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 4064
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 583122
telemt_user_connections_current{user="hello"} 674
telemt_user_octets_from_client{user="hello"} 8992014056 (8.37 GB)
telemt_user_octets_to_client{user="hello"} 217915879948 (202.95 GB)
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 28689.4 (7h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 484350
telemt_connections_bad_total 100898
telemt_handshake_timeouts_total 55212
telemt_upstream_connect_attempt_total 6581
telemt_upstream_connect_success_total 6580
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6581
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3305
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3193
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 216
telemt_me_reconnect_attempts_total 6061
telemt_me_reconnect_success_total 5138
telemt_me_reader_eof_total 5390
telemt_me_idle_close_by_peer_total 5390
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 112235
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 320097
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 704
telemt_desync_full_logged_total 246
telemt_desync_suppressed_total 458
telemt_desync_frames_bucket_total{bucket="1_2"} 243
telemt_desync_frames_bucket_total{bucket="3_10"} 232
telemt_desync_frames_bucket_total{bucket="gt_10"} 229
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 5226
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5126
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 320011
telemt_user_connections_current{user="hello"} 373
telemt_user_octets_from_client{user="hello"} 4503552320 (4.19 GB)
telemt_user_octets_to_client{user="hello"} 97981754004 (91.25 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 28984.6 (8h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 406260
telemt_connections_bad_total 1394
telemt_handshake_timeouts_total 4039
telemt_upstream_connect_attempt_total 6156
telemt_upstream_connect_success_total 6032
telemt_upstream_connect_fail_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 6156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2936
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3048
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 124
telemt_me_keepalive_timeout_total 146
telemt_me_reconnect_attempts_total 5223
telemt_me_reconnect_success_total 4544
telemt_me_reader_eof_total 4804
telemt_me_idle_close_by_peer_total 4804
telemt_me_route_drop_no_conn_total 127725
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 377209
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1057
telemt_desync_full_logged_total 372
telemt_desync_suppressed_total 685
telemt_desync_frames_bucket_total{bucket="1_2"} 341
telemt_desync_frames_bucket_total{bucket="3_10"} 335
telemt_desync_frames_bucket_total{bucket="gt_10"} 381
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 4647
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 4526
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 377174
telemt_user_connections_current{user="hello"} 495
telemt_user_octets_from_client{user="hello"} 5980100628 (5.57 GB)
telemt_user_octets_to_client{user="hello"} 155407179272 (144.73 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 57
```