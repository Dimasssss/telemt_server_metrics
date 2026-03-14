# Server Metrics 2026-03-14 02:49:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 161476.7 (44h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4683425
telemt_connections_bad_total 39822
telemt_handshake_timeouts_total 108537
telemt_upstream_connect_attempt_total 34135
telemt_upstream_connect_success_total 33908
telemt_upstream_connect_fail_total 227
telemt_upstream_connect_attempts_per_request{bucket="1"} 34135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15264
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 227
telemt_me_keepalive_timeout_total 6726
telemt_me_reconnect_attempts_total 33663
telemt_me_reconnect_success_total 23522
telemt_me_reader_eof_total 25230
telemt_me_idle_close_by_peer_total 25229
telemt_me_route_drop_no_conn_total 1780170
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4295432
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16768
telemt_desync_full_logged_total 4522
telemt_desync_suppressed_total 12246
telemt_desync_frames_bucket_total{bucket="1_2"} 4189
telemt_desync_frames_bucket_total{bucket="3_10"} 6395
telemt_desync_frames_bucket_total{bucket="gt_10"} 6184
telemt_pool_swap_total 139
telemt_me_writer_removed_unexpected_total 24178
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 23509
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 656
telemt_user_connections_total{user="hello"} 4297033
telemt_user_connections_current{user="hello"} 681
telemt_user_octets_from_client{user="hello"} 63027486376 (58.70 GB)
telemt_user_octets_to_client{user="hello"} 1357950403289 (1.24 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 61140.5 (16h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 700713
telemt_connections_bad_total 50975
telemt_handshake_timeouts_total 13135
telemt_upstream_connect_attempt_total 17055
telemt_upstream_connect_success_total 16803
telemt_upstream_connect_fail_total 252
telemt_upstream_connect_attempts_per_request{bucket="1"} 17055
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9362
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7200
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 212
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 252
telemt_me_keepalive_timeout_total 2083
telemt_me_reconnect_attempts_total 15181
telemt_me_reconnect_success_total 11735
telemt_me_reader_eof_total 12450
telemt_me_idle_close_by_peer_total 12449
telemt_me_route_drop_no_conn_total 235366
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 561475
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1689
telemt_desync_full_logged_total 467
telemt_desync_suppressed_total 1222
telemt_desync_frames_bucket_total{bucket="1_2"} 361
telemt_desync_frames_bucket_total{bucket="3_10"} 737
telemt_desync_frames_bucket_total{bucket="gt_10"} 591
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12002
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 11727
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 267
telemt_user_connections_total{user="hello"} 563433
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 6000081185 (5.59 GB)
telemt_user_octets_to_client{user="hello"} 180727531540 (168.32 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 191097.3 (53h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3383399
telemt_connections_bad_total 34991
telemt_handshake_timeouts_total 223445
telemt_upstream_connect_attempt_total 43088
telemt_upstream_connect_success_total 43067
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 43088
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20203
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 232
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10426
telemt_me_reconnect_attempts_total 38197
telemt_me_reconnect_success_total 33234
telemt_me_reader_eof_total 35297
telemt_me_idle_close_by_peer_total 35296
telemt_me_route_drop_no_conn_total 1159287
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2816437
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9355
telemt_desync_full_logged_total 3124
telemt_desync_suppressed_total 6231
telemt_desync_frames_bucket_total{bucket="1_2"} 1610
telemt_desync_frames_bucket_total{bucket="3_10"} 3384
telemt_desync_frames_bucket_total{bucket="gt_10"} 4361
telemt_pool_swap_total 180
telemt_me_writer_removed_unexpected_total 33698
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 33193
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 464
telemt_user_connections_total{user="hello"} 2815661
telemt_user_connections_current{user="hello"} 387
telemt_user_octets_from_client{user="hello"} 45216752200 (42.11 GB)
telemt_user_octets_to_client{user="hello"} 1005929656641 (936.84 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 191099.8 (53h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2261330
telemt_connections_bad_total 22978
telemt_handshake_timeouts_total 247831
telemt_upstream_connect_attempt_total 59925
telemt_upstream_connect_success_total 57460
telemt_upstream_connect_fail_total 2328
telemt_upstream_connect_attempts_per_request{bucket="1"} 59651
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34346
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22948
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2327
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20427
telemt_me_reconnect_attempts_total 49948
telemt_me_reconnect_success_total 40915
telemt_me_reader_eof_total 43887
telemt_me_idle_close_by_peer_total 43880
telemt_me_route_drop_no_conn_total 772721
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1803149
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3811
telemt_desync_full_logged_total 1227
telemt_desync_suppressed_total 2584
telemt_desync_frames_bucket_total{bucket="1_2"} 1016
telemt_desync_frames_bucket_total{bucket="3_10"} 1588
telemt_desync_frames_bucket_total{bucket="gt_10"} 1207
telemt_pool_swap_total 168
telemt_me_writer_removed_unexpected_total 41549
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 40891
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 634
telemt_user_connections_total{user="hello"} 1809081
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 27617528171 (25.72 GB)
telemt_user_octets_to_client{user="hello"} 667184401322 (621.36 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 60533.3 (16h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 701366
telemt_connections_bad_total 7913
telemt_handshake_timeouts_total 8669
telemt_upstream_connect_attempt_total 15584
telemt_upstream_connect_success_total 15159
telemt_upstream_connect_fail_total 425
telemt_upstream_connect_attempts_per_request{bucket="1"} 15584
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7293
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7841
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 425
telemt_me_keepalive_timeout_total 1509
telemt_me_reconnect_attempts_total 45431
telemt_me_reconnect_success_total 12116
telemt_me_reader_eof_total 13466
telemt_me_idle_close_by_peer_total 13465
telemt_me_route_drop_no_conn_total 266248
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 653367
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1698
telemt_desync_full_logged_total 532
telemt_desync_suppressed_total 1166
telemt_desync_frames_bucket_total{bucket="1_2"} 511
telemt_desync_frames_bucket_total{bucket="3_10"} 657
telemt_desync_frames_bucket_total{bucket="gt_10"} 530
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 13264
telemt_me_refill_failed_total 1037
telemt_me_writer_restored_same_endpoint_total 12111
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1148
telemt_user_connections_total{user="hello"} 653248
telemt_user_connections_current{user="hello"} 304
telemt_user_octets_from_client{user="hello"} 11941766020 (11.12 GB)
telemt_user_octets_to_client{user="hello"} 212401834504 (197.81 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 34
```