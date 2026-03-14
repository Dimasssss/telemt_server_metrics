# Server Metrics 2026-03-14 19:02:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 20677.7 (5h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 832657
telemt_connections_bad_total 40360
telemt_handshake_timeouts_total 12077
telemt_upstream_connect_attempt_total 3896
telemt_upstream_connect_success_total 3880
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3896
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1889
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1960
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 3612
telemt_me_reconnect_success_total 2809
telemt_me_reader_eof_total 2952
telemt_me_idle_close_by_peer_total 2952
telemt_me_route_drop_no_conn_total 319134
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 735274
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2503
telemt_desync_full_logged_total 725
telemt_desync_suppressed_total 1778
telemt_desync_frames_bucket_total{bucket="1_2"} 604
telemt_desync_frames_bucket_total{bucket="3_10"} 928
telemt_desync_frames_bucket_total{bucket="gt_10"} 971
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2881
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 2800
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 735208
telemt_user_connections_current{user="hello"} 1723
telemt_user_octets_from_client{user="hello"} 13016081388 (12.12 GB)
telemt_user_octets_to_client{user="hello"} 243961527040 (227.21 GB)
telemt_user_unique_ips_current{user="hello"} 464
telemt_user_unique_ips_recent_window{user="hello"} 220
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 20683.2 (5h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 321242
telemt_connections_bad_total 23056
telemt_handshake_timeouts_total 9637
telemt_upstream_connect_attempt_total 4298
telemt_upstream_connect_success_total 4246
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 4297
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1902
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 384
telemt_me_reconnect_attempts_total 3971
telemt_me_reconnect_success_total 3177
telemt_me_reader_eof_total 3326
telemt_me_idle_close_by_peer_total 3326
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 100316
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 269528
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1116
telemt_desync_full_logged_total 349
telemt_desync_suppressed_total 767
telemt_desync_frames_bucket_total{bucket="1_2"} 445
telemt_desync_frames_bucket_total{bucket="3_10"} 408
telemt_desync_frames_bucket_total{bucket="gt_10"} 263
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3268
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 3161
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 269460
telemt_user_connections_current{user="hello"} 639
telemt_user_octets_from_client{user="hello"} 3716628592 (3.46 GB)
telemt_user_octets_to_client{user="hello"} 95870639736 (89.29 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 20545.8 (5h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 671581
telemt_connections_bad_total 2462
telemt_handshake_timeouts_total 132065
telemt_upstream_connect_attempt_total 4035
telemt_upstream_connect_success_total 4022
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 4035
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2049
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1963
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 6873
telemt_me_reconnect_success_total 2966
telemt_me_reader_eof_total 3185
telemt_me_idle_close_by_peer_total 3185
telemt_me_route_drop_no_conn_total 163368
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 458620
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1595
telemt_desync_full_logged_total 610
telemt_desync_suppressed_total 985
telemt_desync_frames_bucket_total{bucket="1_2"} 215
telemt_desync_frames_bucket_total{bucket="3_10"} 554
telemt_desync_frames_bucket_total{bucket="gt_10"} 826
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3115
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2933
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 149
telemt_user_connections_total{user="hello"} 458514
telemt_user_connections_current{user="hello"} 1134
telemt_user_octets_from_client{user="hello"} 6670302416 (6.21 GB)
telemt_user_octets_to_client{user="hello"} 163151657228 (151.95 GB)
telemt_user_unique_ips_current{user="hello"} 319
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 20400.4 (5h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 371640
telemt_connections_bad_total 85894
telemt_handshake_timeouts_total 44801
telemt_upstream_connect_attempt_total 4864
telemt_upstream_connect_success_total 4863
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4864
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2482
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2311
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 179
telemt_me_reconnect_attempts_total 4731
telemt_me_reconnect_success_total 3815
telemt_me_reader_eof_total 3986
telemt_me_idle_close_by_peer_total 3986
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 83002
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 234938
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 10
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 510
telemt_desync_full_logged_total 172
telemt_desync_suppressed_total 338
telemt_desync_frames_bucket_total{bucket="1_2"} 188
telemt_desync_frames_bucket_total{bucket="3_10"} 156
telemt_desync_frames_bucket_total{bucket="gt_10"} 166
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3886
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3805
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 234876
telemt_user_connections_current{user="hello"} 492
telemt_user_octets_from_client{user="hello"} 3453189304 (3.22 GB)
telemt_user_octets_to_client{user="hello"} 73813526948 (68.74 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 20695.8 (5h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 315446
telemt_connections_bad_total 1233
telemt_handshake_timeouts_total 3505
telemt_upstream_connect_attempt_total 4207
telemt_upstream_connect_success_total 4122
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 4207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2038
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2043
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 115
telemt_me_reconnect_attempts_total 3742
telemt_me_reconnect_success_total 3073
telemt_me_reader_eof_total 3243
telemt_me_idle_close_by_peer_total 3243
telemt_me_route_drop_no_conn_total 98487
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 292364
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 730
telemt_desync_full_logged_total 278
telemt_desync_suppressed_total 452
telemt_desync_frames_bucket_total{bucket="1_2"} 266
telemt_desync_frames_bucket_total{bucket="3_10"} 218
telemt_desync_frames_bucket_total{bucket="gt_10"} 246
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3156
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 3055
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 292353
telemt_user_connections_current{user="hello"} 727
telemt_user_octets_from_client{user="hello"} 4546471840 (4.23 GB)
telemt_user_octets_to_client{user="hello"} 125060947420 (116.47 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 101
```