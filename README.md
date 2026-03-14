# Server Metrics 2026-03-14 02:09:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 159023.1 (44h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4657582
telemt_connections_bad_total 39808
telemt_handshake_timeouts_total 108336
telemt_upstream_connect_attempt_total 33597
telemt_upstream_connect_success_total 33372
telemt_upstream_connect_fail_total 225
telemt_upstream_connect_attempts_per_request{bucket="1"} 33597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18218
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15009
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 225
telemt_me_keepalive_timeout_total 6711
telemt_me_reconnect_attempts_total 33257
telemt_me_reconnect_success_total 23118
telemt_me_reader_eof_total 24791
telemt_me_idle_close_by_peer_total 24790
telemt_me_route_drop_no_conn_total 1763390
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4270279
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16742
telemt_desync_full_logged_total 4513
telemt_desync_suppressed_total 12229
telemt_desync_frames_bucket_total{bucket="1_2"} 4184
telemt_desync_frames_bucket_total{bucket="3_10"} 6391
telemt_desync_frames_bucket_total{bucket="gt_10"} 6167
telemt_pool_swap_total 136
telemt_me_writer_removed_unexpected_total 23767
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 23105
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 649
telemt_user_connections_total{user="hello"} 4272134
telemt_user_connections_current{user="hello"} 656
telemt_user_octets_from_client{user="hello"} 62763335116 (58.45 GB)
telemt_user_octets_to_client{user="hello"} 1348539380921 (1.23 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 58686.8 (16h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 692777
telemt_connections_bad_total 50961
telemt_handshake_timeouts_total 13092
telemt_upstream_connect_attempt_total 16351
telemt_upstream_connect_success_total 16101
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 16351
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6869
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 212
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_keepalive_timeout_total 2056
telemt_me_reconnect_attempts_total 14565
telemt_me_reconnect_success_total 11121
telemt_me_reader_eof_total 11798
telemt_me_idle_close_by_peer_total 11797
telemt_me_route_drop_no_conn_total 232318
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 553910
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1660
telemt_desync_full_logged_total 453
telemt_desync_suppressed_total 1207
telemt_desync_frames_bucket_total{bucket="1_2"} 357
telemt_desync_frames_bucket_total{bucket="3_10"} 719
telemt_desync_frames_bucket_total{bucket="gt_10"} 584
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 11383
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 11113
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 262
telemt_user_connections_total{user="hello"} 555861
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 5957665593 (5.55 GB)
telemt_user_octets_to_client{user="hello"} 178846712100 (166.56 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 188643.4 (52h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3368467
telemt_connections_bad_total 34943
telemt_handshake_timeouts_total 223253
telemt_upstream_connect_attempt_total 42448
telemt_upstream_connect_success_total 42427
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 42448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19906
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 230
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10413
telemt_me_reconnect_attempts_total 37686
telemt_me_reconnect_success_total 32725
telemt_me_reader_eof_total 34752
telemt_me_idle_close_by_peer_total 34751
telemt_me_route_drop_no_conn_total 1155111
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2802154
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9263
telemt_desync_full_logged_total 3106
telemt_desync_suppressed_total 6157
telemt_desync_frames_bucket_total{bucket="1_2"} 1579
telemt_desync_frames_bucket_total{bucket="3_10"} 3356
telemt_desync_frames_bucket_total{bucket="gt_10"} 4328
telemt_pool_swap_total 177
telemt_me_writer_removed_unexpected_total 33186
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 32684
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 461
telemt_user_connections_total{user="hello"} 2801379
telemt_user_connections_current{user="hello"} 291
telemt_user_octets_from_client{user="hello"} 45118858100 (42.02 GB)
telemt_user_octets_to_client{user="hello"} 1003472818073 (934.56 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 188646.0 (52h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2247674
telemt_connections_bad_total 22946
telemt_handshake_timeouts_total 244650
telemt_upstream_connect_attempt_total 59071
telemt_upstream_connect_success_total 56610
telemt_upstream_connect_fail_total 2323
telemt_upstream_connect_attempts_per_request{bucket="1"} 58796
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33836
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22608
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2322
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20412
telemt_me_reconnect_attempts_total 49232
telemt_me_reconnect_success_total 40200
telemt_me_reader_eof_total 43110
telemt_me_idle_close_by_peer_total 43103
telemt_me_route_drop_no_conn_total 770295
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1795910
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3806
telemt_desync_full_logged_total 1223
telemt_desync_suppressed_total 2583
telemt_desync_frames_bucket_total{bucket="1_2"} 1012
telemt_desync_frames_bucket_total{bucket="3_10"} 1588
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 165
telemt_me_writer_removed_unexpected_total 40831
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 40176
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 631
telemt_user_connections_total{user="hello"} 1801831
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 27562990051 (25.67 GB)
telemt_user_octets_to_client{user="hello"} 665763384974 (620.04 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 58079.4 (16h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 692392
telemt_connections_bad_total 7904
telemt_handshake_timeouts_total 8651
telemt_upstream_connect_attempt_total 14619
telemt_upstream_connect_success_total 14215
telemt_upstream_connect_fail_total 404
telemt_upstream_connect_attempts_per_request{bucket="1"} 14619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6840
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 404
telemt_me_keepalive_timeout_total 1497
telemt_me_reconnect_attempts_total 43465
telemt_me_reconnect_success_total 11302
telemt_me_reader_eof_total 12610
telemt_me_idle_close_by_peer_total 12609
telemt_me_route_drop_no_conn_total 262851
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 644595
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1657
telemt_desync_full_logged_total 519
telemt_desync_suppressed_total 1138
telemt_desync_frames_bucket_total{bucket="1_2"} 498
telemt_desync_frames_bucket_total{bucket="3_10"} 647
telemt_desync_frames_bucket_total{bucket="gt_10"} 512
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 12408
telemt_me_refill_failed_total 1001
telemt_me_writer_restored_same_endpoint_total 11297
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1106
telemt_user_connections_total{user="hello"} 644482
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 10606991140 (9.88 GB)
telemt_user_octets_to_client{user="hello"} 210207297136 (195.77 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 19
```