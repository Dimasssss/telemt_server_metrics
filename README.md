# Server Metrics 2026-03-14 18:41:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 19450.2 (5h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 787430
telemt_connections_bad_total 40144
telemt_handshake_timeouts_total 10987
telemt_upstream_connect_attempt_total 3742
telemt_upstream_connect_success_total 3727
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 3742
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1825
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1874
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 3502
telemt_me_reconnect_success_total 2700
telemt_me_reader_eof_total 2835
telemt_me_idle_close_by_peer_total 2835
telemt_me_route_drop_no_conn_total 301558
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 697081
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2384
telemt_desync_full_logged_total 687
telemt_desync_suppressed_total 1697
telemt_desync_frames_bucket_total{bucket="1_2"} 567
telemt_desync_frames_bucket_total{bucket="3_10"} 893
telemt_desync_frames_bucket_total{bucket="gt_10"} 924
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2768
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 2691
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 697010
telemt_user_connections_current{user="hello"} 1760
telemt_user_octets_from_client{user="hello"} 12045586708 (11.22 GB)
telemt_user_octets_to_client{user="hello"} 230839970036 (214.99 GB)
telemt_user_unique_ips_current{user="hello"} 464
telemt_user_unique_ips_recent_window{user="hello"} 212
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 19455.6 (5h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 304811
telemt_connections_bad_total 22782
telemt_handshake_timeouts_total 9006
telemt_upstream_connect_attempt_total 4056
telemt_upstream_connect_success_total 4006
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 4056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1763
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 319
telemt_me_reconnect_attempts_total 3773
telemt_me_reconnect_success_total 2981
telemt_me_reader_eof_total 3117
telemt_me_idle_close_by_peer_total 3117
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 95349
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 254455
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1035
telemt_desync_full_logged_total 320
telemt_desync_suppressed_total 715
telemt_desync_frames_bucket_total{bucket="1_2"} 405
telemt_desync_frames_bucket_total{bucket="3_10"} 388
telemt_desync_frames_bucket_total{bucket="gt_10"} 242
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 3070
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 2965
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 254380
telemt_user_connections_current{user="hello"} 616
telemt_user_octets_from_client{user="hello"} 3569371788 (3.32 GB)
telemt_user_octets_to_client{user="hello"} 92010636612 (85.69 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 19318.5 (5h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 642501
telemt_connections_bad_total 2447
telemt_handshake_timeouts_total 131080
telemt_upstream_connect_attempt_total 3826
telemt_upstream_connect_success_total 3813
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 3826
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1933
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1871
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 90
telemt_me_reconnect_attempts_total 6709
telemt_me_reconnect_success_total 2802
telemt_me_reader_eof_total 3012
telemt_me_idle_close_by_peer_total 3012
telemt_me_route_drop_no_conn_total 156083
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 435426
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1470
telemt_desync_full_logged_total 566
telemt_desync_suppressed_total 904
telemt_desync_frames_bucket_total{bucket="1_2"} 193
telemt_desync_frames_bucket_total{bucket="3_10"} 513
telemt_desync_frames_bucket_total{bucket="gt_10"} 764
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2949
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2769
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 435331
telemt_user_connections_current{user="hello"} 1030
telemt_user_octets_from_client{user="hello"} 6454446180 (6.01 GB)
telemt_user_octets_to_client{user="hello"} 155755958416 (145.06 GB)
telemt_user_unique_ips_current{user="hello"} 277
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 19173.0 (5h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 352187
telemt_connections_bad_total 82438
telemt_handshake_timeouts_total 43238
telemt_upstream_connect_attempt_total 4650
telemt_upstream_connect_success_total 4649
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2377
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2203
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 127
telemt_me_reconnect_attempts_total 4562
telemt_me_reconnect_success_total 3647
telemt_me_reader_eof_total 3810
telemt_me_idle_close_by_peer_total 3810
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 78040
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 220768
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 10
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 495
telemt_desync_full_logged_total 166
telemt_desync_suppressed_total 329
telemt_desync_frames_bucket_total{bucket="1_2"} 183
telemt_desync_frames_bucket_total{bucket="3_10"} 151
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3714
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3637
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 220719
telemt_user_connections_current{user="hello"} 465
telemt_user_octets_from_client{user="hello"} 3288712004 (3.06 GB)
telemt_user_octets_to_client{user="hello"} 69382348912 (64.62 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 19468.5 (5h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 298604
telemt_connections_bad_total 1121
telemt_handshake_timeouts_total 3436
telemt_upstream_connect_attempt_total 4009
telemt_upstream_connect_success_total 3929
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 4009
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1950
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1938
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 3594
telemt_me_reconnect_success_total 2925
telemt_me_reader_eof_total 3085
telemt_me_idle_close_by_peer_total 3085
telemt_me_route_drop_no_conn_total 93748
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 276432
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 680
telemt_desync_full_logged_total 265
telemt_desync_suppressed_total 415
telemt_desync_frames_bucket_total{bucket="1_2"} 248
telemt_desync_frames_bucket_total{bucket="3_10"} 208
telemt_desync_frames_bucket_total{bucket="gt_10"} 224
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3005
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 2907
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 276418
telemt_user_connections_current{user="hello"} 827
telemt_user_octets_from_client{user="hello"} 4266904680 (3.97 GB)
telemt_user_octets_to_client{user="hello"} 119601361732 (111.39 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 88
```