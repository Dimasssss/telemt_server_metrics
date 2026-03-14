# Server Metrics 2026-03-14 18:57:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 20370.6 (5h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 819274
telemt_connections_bad_total 40356
telemt_handshake_timeouts_total 11849
telemt_upstream_connect_attempt_total 3877
telemt_upstream_connect_success_total 3861
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3877
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1948
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 3593
telemt_me_reconnect_success_total 2790
telemt_me_reader_eof_total 2931
telemt_me_idle_close_by_peer_total 2931
telemt_me_route_drop_no_conn_total 314594
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 725633
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2489
telemt_desync_full_logged_total 717
telemt_desync_suppressed_total 1772
telemt_desync_frames_bucket_total{bucket="1_2"} 598
telemt_desync_frames_bucket_total{bucket="3_10"} 925
telemt_desync_frames_bucket_total{bucket="gt_10"} 966
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2860
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 2781
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 725569
telemt_user_connections_current{user="hello"} 1750
telemt_user_octets_from_client{user="hello"} 12755611636 (11.88 GB)
telemt_user_octets_to_client{user="hello"} 240950685572 (224.40 GB)
telemt_user_unique_ips_current{user="hello"} 475
telemt_user_unique_ips_recent_window{user="hello"} 203
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 20376.0 (5h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 317086
telemt_connections_bad_total 23055
telemt_handshake_timeouts_total 9395
telemt_upstream_connect_attempt_total 4271
telemt_upstream_connect_success_total 4220
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 4271
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1886
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 383
telemt_me_reconnect_attempts_total 3944
telemt_me_reconnect_success_total 3151
telemt_me_reader_eof_total 3299
telemt_me_idle_close_by_peer_total 3299
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 98976
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 265798
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1095
telemt_desync_full_logged_total 341
telemt_desync_suppressed_total 754
telemt_desync_frames_bucket_total{bucket="1_2"} 432
telemt_desync_frames_bucket_total{bucket="3_10"} 407
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3241
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 3135
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 265731
telemt_user_connections_current{user="hello"} 566
telemt_user_octets_from_client{user="hello"} 3698263400 (3.44 GB)
telemt_user_octets_to_client{user="hello"} 95020120516 (88.49 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 20238.8 (5h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 662986
telemt_connections_bad_total 2462
telemt_handshake_timeouts_total 131220
telemt_upstream_connect_attempt_total 4001
telemt_upstream_connect_success_total 3988
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 4001
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2030
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1948
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 93
telemt_me_reconnect_attempts_total 6839
telemt_me_reconnect_success_total 2932
telemt_me_reader_eof_total 3149
telemt_me_idle_close_by_peer_total 3149
telemt_me_route_drop_no_conn_total 161498
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 452485
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1554
telemt_desync_full_logged_total 601
telemt_desync_suppressed_total 953
telemt_desync_frames_bucket_total{bucket="1_2"} 210
telemt_desync_frames_bucket_total{bucket="3_10"} 537
telemt_desync_frames_bucket_total{bucket="gt_10"} 807
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3079
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2899
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 452393
telemt_user_connections_current{user="hello"} 1076
telemt_user_octets_from_client{user="hello"} 6594742920 (6.14 GB)
telemt_user_octets_to_client{user="hello"} 160976668944 (149.92 GB)
telemt_user_unique_ips_current{user="hello"} 308
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 20093.3 (5h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 366547
telemt_connections_bad_total 85168
telemt_handshake_timeouts_total 44167
telemt_upstream_connect_attempt_total 4822
telemt_upstream_connect_success_total 4821
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4822
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2289
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 178
telemt_me_reconnect_attempts_total 4689
telemt_me_reconnect_success_total 3773
telemt_me_reader_eof_total 3942
telemt_me_idle_close_by_peer_total 3942
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 81862
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 231331
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 10
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 506
telemt_desync_full_logged_total 170
telemt_desync_suppressed_total 336
telemt_desync_frames_bucket_total{bucket="1_2"} 187
telemt_desync_frames_bucket_total{bucket="3_10"} 153
telemt_desync_frames_bucket_total{bucket="gt_10"} 166
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3842
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3763
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 231269
telemt_user_connections_current{user="hello"} 455
telemt_user_octets_from_client{user="hello"} 3402942864 (3.17 GB)
telemt_user_octets_to_client{user="hello"} 71967923736 (67.03 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 20388.9 (5h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 311399
telemt_connections_bad_total 1232
telemt_handshake_timeouts_total 3492
telemt_upstream_connect_attempt_total 4184
telemt_upstream_connect_success_total 4099
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 4184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2027
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2031
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 114
telemt_me_reconnect_attempts_total 3719
telemt_me_reconnect_success_total 3050
telemt_me_reader_eof_total 3220
telemt_me_idle_close_by_peer_total 3220
telemt_me_route_drop_no_conn_total 97203
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 288491
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 719
telemt_desync_full_logged_total 275
telemt_desync_suppressed_total 444
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 215
telemt_desync_frames_bucket_total{bucket="gt_10"} 244
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3133
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 3032
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 288476
telemt_user_connections_current{user="hello"} 731
telemt_user_octets_from_client{user="hello"} 4467329452 (4.16 GB)
telemt_user_octets_to_client{user="hello"} 123912381940 (115.40 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 86
```