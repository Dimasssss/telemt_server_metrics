# Server Metrics 2026-03-07 02:22:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 29681.7 (8h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 331783
telemt_connections_bad_total 3894
telemt_handshake_timeouts_total 9613
telemt_upstream_connect_attempt_total 98547
telemt_upstream_connect_success_total 95577
telemt_upstream_connect_fail_total 2817
telemt_upstream_connect_attempts_per_request{bucket="1"} 98394
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36149
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 59135
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 119
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 174
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2817
telemt_me_keepalive_timeout_total 2010
telemt_me_reconnect_attempts_total 61596
telemt_me_reconnect_success_total 58872
telemt_me_reader_eof_total 61550
telemt_me_idle_close_by_peer_total 61547
telemt_me_route_drop_no_conn_total 124274
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 241
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1130
telemt_desync_full_logged_total 311
telemt_desync_suppressed_total 819
telemt_desync_frames_bucket_total{bucket="1_2"} 307
telemt_desync_frames_bucket_total{bucket="3_10"} 506
telemt_desync_frames_bucket_total{bucket="gt_10"} 317
telemt_pool_swap_total 14
telemt_pool_force_close_total 628
telemt_pool_stale_pick_total 187
telemt_me_writer_removed_unexpected_total 61664
telemt_me_writer_restored_same_endpoint_total 58700
telemt_me_writer_restored_fallback_total 166
telemt_me_async_recovery_trigger_total 54193
telemt_me_writer_removed_unexpected_minus_restored_total 2798
telemt_user_connections_total{user="hello"} 302137
telemt_user_connections_current{user="hello"} 332
telemt_user_octets_from_client{user="hello"} 4454107096 (4.15 GB)
telemt_user_octets_to_client{user="hello"} 131755277980 (122.71 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 29681.6 (8h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145796
telemt_connections_bad_total 125
telemt_handshake_timeouts_total 19920
telemt_upstream_connect_attempt_total 205300
telemt_upstream_connect_success_total 205298
telemt_upstream_connect_attempts_per_request{bucket="1"} 205298
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 158959
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46304
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 1556
telemt_me_reconnect_attempts_total 162163
telemt_me_reconnect_success_total 161693
telemt_me_reader_eof_total 146441
telemt_me_idle_close_by_peer_total 146436
telemt_me_route_drop_no_conn_total 44535
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 256
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 847
telemt_desync_full_logged_total 225
telemt_desync_suppressed_total 622
telemt_desync_frames_bucket_total{bucket="1_2"} 153
telemt_desync_frames_bucket_total{bucket="3_10"} 420
telemt_desync_frames_bucket_total{bucket="gt_10"} 274
telemt_pool_swap_total 22
telemt_pool_force_close_total 1440
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 146482
telemt_me_writer_restored_same_endpoint_total 161691
telemt_me_async_recovery_trigger_total 54186
telemt_user_connections_total{user="hello"} 118634
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 1620050496 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 40089238604 (37.34 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 29681.4 (8h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 258970
telemt_connections_bad_total 1456
telemt_handshake_timeouts_total 4370
telemt_upstream_connect_attempt_total 155924
telemt_upstream_connect_success_total 155696
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 155780
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106540
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 48851
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 299
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 2757
telemt_me_reconnect_attempts_total 118399
telemt_me_reconnect_success_total 118307
telemt_me_reader_eof_total 120152
telemt_me_idle_close_by_peer_total 120147
telemt_me_route_drop_no_conn_total 94850
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 243
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1095
telemt_desync_full_logged_total 285
telemt_desync_suppressed_total 810
telemt_desync_frames_bucket_total{bucket="1_2"} 209
telemt_desync_frames_bucket_total{bucket="3_10"} 443
telemt_desync_frames_bucket_total{bucket="gt_10"} 443
telemt_pool_swap_total 16
telemt_pool_force_close_total 405
telemt_pool_stale_pick_total 127
telemt_me_writer_removed_unexpected_total 120343
telemt_me_writer_restored_same_endpoint_total 118300
telemt_me_async_recovery_trigger_total 162299
telemt_me_writer_removed_unexpected_minus_restored_total 2043
telemt_user_connections_total{user="hello"} 242087
telemt_user_connections_current{user="hello"} 217
telemt_user_octets_from_client{user="hello"} 23799776680 (22.17 GB)
telemt_user_octets_to_client{user="hello"} 68152365024 (63.47 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 29681.8 (8h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 268448
telemt_connections_bad_total 83195
telemt_handshake_timeouts_total 17443
telemt_upstream_connect_attempt_total 58653
telemt_upstream_connect_success_total 58563
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 58606
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34687
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 1115
telemt_me_reconnect_attempts_total 20942
telemt_me_reconnect_success_total 20907
telemt_me_reader_eof_total 28436
telemt_me_idle_close_by_peer_total 28434
telemt_me_route_drop_no_conn_total 72712
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 246
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 257
telemt_desync_full_logged_total 110
telemt_desync_suppressed_total 147
telemt_desync_frames_bucket_total{bucket="1_2"} 82
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 14
telemt_pool_force_close_total 498
telemt_pool_stale_pick_total 474
telemt_me_writer_removed_unexpected_total 28441
telemt_me_writer_restored_same_endpoint_total 20902
telemt_me_writer_removed_unexpected_minus_restored_total 7539
telemt_user_connections_total{user="hello"} 163554
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 1805886252 (1.68 GB)
telemt_user_octets_to_client{user="hello"} 51611616196 (48.07 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 29680.3 (8h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 225651
telemt_connections_bad_total 523
telemt_handshake_timeouts_total 2929
telemt_upstream_connect_attempt_total 50322
telemt_upstream_connect_success_total 50133
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 50157
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19184
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30578
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 1336
telemt_me_reconnect_attempts_total 14698
telemt_me_reconnect_success_total 14656
telemt_me_reader_eof_total 20222
telemt_me_idle_close_by_peer_total 20220
telemt_me_route_drop_no_conn_total 73961
telemt_me_route_drop_channel_closed_total 4
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 242
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 813
telemt_desync_full_logged_total 211
telemt_desync_suppressed_total 602
telemt_desync_frames_bucket_total{bucket="1_2"} 277
telemt_desync_frames_bucket_total{bucket="3_10"} 266
telemt_desync_frames_bucket_total{bucket="gt_10"} 270
telemt_pool_swap_total 18
telemt_pool_force_close_total 486
telemt_pool_stale_pick_total 218
telemt_me_writer_removed_unexpected_total 20291
telemt_me_writer_restored_same_endpoint_total 14648
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 5639
telemt_user_connections_total{user="hello"} 207264
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 10324903368 (9.62 GB)
telemt_user_octets_to_client{user="hello"} 78559438088 (73.16 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 26
```