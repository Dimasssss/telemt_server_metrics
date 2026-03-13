# Server Metrics 2026-03-13 23:15:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 148595.0 (41h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4561646
telemt_connections_bad_total 38380
telemt_handshake_timeouts_total 107625
telemt_upstream_connect_attempt_total 31103
telemt_upstream_connect_success_total 30888
telemt_upstream_connect_fail_total 214
telemt_upstream_connect_attempts_per_request{bucket="1"} 31102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16962
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13781
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 214
telemt_me_keepalive_timeout_total 6647
telemt_me_reconnect_attempts_total 31264
telemt_me_reconnect_success_total 21136
telemt_me_reader_eof_total 22671
telemt_me_idle_close_by_peer_total 22670
telemt_me_route_drop_no_conn_total 1724416
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4179665
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16594
telemt_desync_full_logged_total 4468
telemt_desync_suppressed_total 12126
telemt_desync_frames_bucket_total{bucket="1_2"} 4131
telemt_desync_frames_bucket_total{bucket="3_10"} 6348
telemt_desync_frames_bucket_total{bucket="gt_10"} 6115
telemt_pool_swap_total 126
telemt_me_writer_removed_unexpected_total 21759
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 21123
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 623
telemt_user_connections_total{user="hello"} 4181597
telemt_user_connections_current{user="hello"} 650
telemt_user_octets_from_client{user="hello"} 61382649480 (57.17 GB)
telemt_user_octets_to_client{user="hello"} 1322156812781 (1.20 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 48258.8 (13h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 606401
telemt_connections_bad_total 44551
telemt_handshake_timeouts_total 12550
telemt_upstream_connect_attempt_total 13683
telemt_upstream_connect_success_total 13447
telemt_upstream_connect_fail_total 236
telemt_upstream_connect_attempts_per_request{bucket="1"} 13683
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5491
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 236
telemt_me_keepalive_timeout_total 1921
telemt_me_reconnect_attempts_total 12431
telemt_me_reconnect_success_total 8995
telemt_me_reader_eof_total 9533
telemt_me_idle_close_by_peer_total 9532
telemt_me_route_drop_no_conn_total 220020
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 523122
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1643
telemt_desync_full_logged_total 444
telemt_desync_suppressed_total 1199
telemt_desync_frames_bucket_total{bucket="1_2"} 348
telemt_desync_frames_bucket_total{bucket="3_10"} 712
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 9234
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 8987
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 239
telemt_user_connections_total{user="hello"} 525067
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 5779568413 (5.38 GB)
telemt_user_octets_to_client{user="hello"} 170816753788 (159.09 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 178215.3 (49h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3309987
telemt_connections_bad_total 31941
telemt_handshake_timeouts_total 221365
telemt_upstream_connect_attempt_total 39533
telemt_upstream_connect_success_total 39512
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 39533
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20614
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18669
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10334
telemt_me_reconnect_attempts_total 35290
telemt_me_reconnect_success_total 30337
telemt_me_reader_eof_total 32199
telemt_me_idle_close_by_peer_total 32198
telemt_me_route_drop_no_conn_total 1135073
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2749883
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9021
telemt_desync_full_logged_total 3033
telemt_desync_suppressed_total 5988
telemt_desync_frames_bucket_total{bucket="1_2"} 1514
telemt_desync_frames_bucket_total{bucket="3_10"} 3269
telemt_desync_frames_bucket_total{bucket="gt_10"} 4238
telemt_pool_swap_total 165
telemt_me_writer_removed_unexpected_total 30781
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 30296
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 444
telemt_user_connections_total{user="hello"} 2749135
telemt_user_connections_current{user="hello"} 327
telemt_user_octets_from_client{user="hello"} 44713502660 (41.64 GB)
telemt_user_octets_to_client{user="hello"} 972132007157 (905.37 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 178218.0 (49h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2174614
telemt_connections_bad_total 22851
telemt_handshake_timeouts_total 227452
telemt_upstream_connect_attempt_total 55489
telemt_upstream_connect_success_total 53038
telemt_upstream_connect_fail_total 2314
telemt_upstream_connect_attempts_per_request{bucket="1"} 55215
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31800
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21072
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2313
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20345
telemt_me_reconnect_attempts_total 46178
telemt_me_reconnect_success_total 37158
telemt_me_reader_eof_total 39847
telemt_me_idle_close_by_peer_total 39840
telemt_me_route_drop_no_conn_total 759204
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1766109
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3795
telemt_desync_full_logged_total 1216
telemt_desync_suppressed_total 2579
telemt_desync_frames_bucket_total{bucket="1_2"} 1002
telemt_desync_frames_bucket_total{bucket="3_10"} 1587
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 155
telemt_me_writer_removed_unexpected_total 37759
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 37134
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 601
telemt_user_connections_total{user="hello"} 1771996
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 27333451847 (25.46 GB)
telemt_user_octets_to_client{user="hello"} 661058248106 (615.66 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 47651.5 (13h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 652245
telemt_connections_bad_total 7853
telemt_handshake_timeouts_total 7066
telemt_upstream_connect_attempt_total 10948
telemt_upstream_connect_success_total 10609
telemt_upstream_connect_fail_total 339
telemt_upstream_connect_attempts_per_request{bucket="1"} 10948
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5073
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5511
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 339
telemt_me_keepalive_timeout_total 1439
telemt_me_reconnect_attempts_total 37948
telemt_me_reconnect_success_total 8229
telemt_me_reader_eof_total 9304
telemt_me_idle_close_by_peer_total 9303
telemt_me_route_drop_no_conn_total 247332
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 607777
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1603
telemt_desync_full_logged_total 504
telemt_desync_suppressed_total 1099
telemt_desync_frames_bucket_total{bucket="1_2"} 487
telemt_desync_frames_bucket_total{bucket="3_10"} 625
telemt_desync_frames_bucket_total{bucket="gt_10"} 491
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 9230
telemt_me_refill_failed_total 925
telemt_me_writer_restored_same_endpoint_total 8224
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1001
telemt_user_connections_total{user="hello"} 607682
telemt_user_connections_current{user="hello"} 305
telemt_user_octets_from_client{user="hello"} 9707984832 (9.04 GB)
telemt_user_octets_to_client{user="hello"} 199223108268 (185.54 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 27
```