# Server Metrics 2026-03-07 01:26:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 26292.5 (7h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 315485
telemt_connections_bad_total 3695
telemt_handshake_timeouts_total 9471
telemt_upstream_connect_attempt_total 80990
telemt_upstream_connect_success_total 78738
telemt_upstream_connect_fail_total 2114
telemt_upstream_connect_attempts_per_request{bucket="1"} 80852
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29605
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 48891
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2114
telemt_me_keepalive_timeout_total 1754
telemt_me_reconnect_attempts_total 48809
telemt_me_reconnect_success_total 46765
telemt_me_reader_eof_total 49303
telemt_me_idle_close_by_peer_total 49303
telemt_me_route_drop_no_conn_total 119398
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 218
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1008
telemt_desync_full_logged_total 274
telemt_desync_suppressed_total 734
telemt_desync_frames_bucket_total{bucket="1_2"} 279
telemt_desync_frames_bucket_total{bucket="3_10"} 454
telemt_desync_frames_bucket_total{bucket="gt_10"} 275
telemt_pool_swap_total 12
telemt_pool_force_close_total 570
telemt_pool_stale_pick_total 187
telemt_me_writer_removed_unexpected_total 49416
telemt_me_writer_restored_same_endpoint_total 46635
telemt_me_writer_restored_fallback_total 124
telemt_me_async_recovery_trigger_total 40713
telemt_me_writer_removed_unexpected_minus_restored_total 2657
telemt_user_connections_total{user="hello"} 286786
telemt_user_connections_current{user="hello"} 282
telemt_user_octets_from_client{user="hello"} 4349186300 (4.05 GB)
telemt_user_octets_to_client{user="hello"} 124320387772 (115.78 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 26292.4 (7h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136091
telemt_connections_bad_total 122
telemt_handshake_timeouts_total 16972
telemt_upstream_connect_attempt_total 163700
telemt_upstream_connect_success_total 163698
telemt_upstream_connect_attempts_per_request{bucket="1"} 163698
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 122681
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40983
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 1320
telemt_me_reconnect_attempts_total 125868
telemt_me_reconnect_success_total 125558
telemt_me_reader_eof_total 113940
telemt_me_idle_close_by_peer_total 113935
telemt_me_route_drop_no_conn_total 43152
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 231
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 812
telemt_desync_full_logged_total 216
telemt_desync_suppressed_total 596
telemt_desync_frames_bucket_total{bucket="1_2"} 143
telemt_desync_frames_bucket_total{bucket="3_10"} 407
telemt_desync_frames_bucket_total{bucket="gt_10"} 262
telemt_pool_swap_total 19
telemt_pool_force_close_total 1171
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 113970
telemt_me_writer_restored_same_endpoint_total 125556
telemt_me_async_recovery_trigger_total 40706
telemt_user_connections_total{user="hello"} 112370
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 1578579164 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 38715441016 (36.06 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 26292.4 (7h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 244428
telemt_connections_bad_total 1273
telemt_handshake_timeouts_total 3603
telemt_upstream_connect_attempt_total 118701
telemt_upstream_connect_success_total 118504
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 118576
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 77903
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40364
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 233
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 2364
telemt_me_reconnect_attempts_total 85922
telemt_me_reconnect_success_total 85845
telemt_me_reader_eof_total 88174
telemt_me_idle_close_by_peer_total 88169
telemt_me_route_drop_no_conn_total 91667
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 220
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1063
telemt_desync_full_logged_total 273
telemt_desync_suppressed_total 790
telemt_desync_frames_bucket_total{bucket="1_2"} 202
telemt_desync_frames_bucket_total{bucket="3_10"} 434
telemt_desync_frames_bucket_total{bucket="gt_10"} 427
telemt_pool_swap_total 14
telemt_pool_force_close_total 372
telemt_pool_stale_pick_total 126
telemt_me_writer_removed_unexpected_total 88362
telemt_me_writer_restored_same_endpoint_total 85838
telemt_me_async_recovery_trigger_total 121905
telemt_me_writer_removed_unexpected_minus_restored_total 2524
telemt_user_connections_total{user="hello"} 228653
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 21805854288 (20.31 GB)
telemt_user_octets_to_client{user="hello"} 64918548656 (60.46 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 26292.7 (7h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 251568
telemt_connections_bad_total 74528
telemt_handshake_timeouts_total 16960
telemt_upstream_connect_attempt_total 48761
telemt_upstream_connect_success_total 48672
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 48713
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29156
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 944
telemt_me_reconnect_attempts_total 16214
telemt_me_reconnect_success_total 16185
telemt_me_reader_eof_total 22230
telemt_me_idle_close_by_peer_total 22228
telemt_me_route_drop_no_conn_total 66928
telemt_me_single_endpoint_shadow_rotate_total 224
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 222
telemt_desync_full_logged_total 99
telemt_desync_suppressed_total 123
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 81
telemt_desync_frames_bucket_total{bucket="gt_10"} 64
telemt_pool_swap_total 13
telemt_pool_force_close_total 453
telemt_pool_stale_pick_total 474
telemt_me_writer_removed_unexpected_total 22235
telemt_me_writer_restored_same_endpoint_total 16180
telemt_me_writer_removed_unexpected_minus_restored_total 6055
telemt_user_connections_total{user="hello"} 155991
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 1748634032 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 50416081248 (46.95 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 26291.1 (7h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 214443
telemt_connections_bad_total 514
telemt_handshake_timeouts_total 2595
telemt_upstream_connect_attempt_total 44217
telemt_upstream_connect_success_total 44052
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 44072
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26566
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 283
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 1215
telemt_me_reconnect_attempts_total 13164
telemt_me_reconnect_success_total 13129
telemt_me_reader_eof_total 18004
telemt_me_idle_close_by_peer_total 18002
telemt_me_route_drop_no_conn_total 71518
telemt_me_route_drop_channel_closed_total 4
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 219
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 801
telemt_desync_full_logged_total 208
telemt_desync_suppressed_total 593
telemt_desync_frames_bucket_total{bucket="1_2"} 273
telemt_desync_frames_bucket_total{bucket="3_10"} 264
telemt_desync_frames_bucket_total{bucket="gt_10"} 264
telemt_pool_swap_total 15
telemt_pool_force_close_total 453
telemt_pool_stale_pick_total 215
telemt_me_writer_removed_unexpected_total 18073
telemt_me_writer_restored_same_endpoint_total 13121
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 4948
telemt_user_connections_total{user="hello"} 196914
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 10223017108 (9.52 GB)
telemt_user_octets_to_client{user="hello"} 68337469716 (63.64 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 26
```