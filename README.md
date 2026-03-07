# Server Metrics 2026-03-07 01:31:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 26601.3 (7h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 316692
telemt_connections_bad_total 3695
telemt_handshake_timeouts_total 9512
telemt_upstream_connect_attempt_total 82480
telemt_upstream_connect_success_total 80151
telemt_upstream_connect_fail_total 2193
telemt_upstream_connect_attempts_per_request{bucket="1"} 82344
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29989
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 49919
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2193
telemt_me_keepalive_timeout_total 1781
telemt_me_reconnect_attempts_total 49826
telemt_me_reconnect_success_total 47706
telemt_me_reader_eof_total 50426
telemt_me_idle_close_by_peer_total 50426
telemt_me_route_drop_no_conn_total 120137
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
telemt_me_writer_removed_unexpected_total 50539
telemt_me_writer_restored_same_endpoint_total 47571
telemt_me_writer_restored_fallback_total 129
telemt_me_async_recovery_trigger_total 41942
telemt_me_writer_removed_unexpected_minus_restored_total 2839
telemt_user_connections_total{user="hello"} 287923
telemt_user_connections_current{user="hello"} 335
telemt_user_octets_from_client{user="hello"} 4357310144 (4.06 GB)
telemt_user_octets_to_client{user="hello"} 124690499344 (116.13 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 26601.2 (7h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136869
telemt_connections_bad_total 123
telemt_handshake_timeouts_total 17158
telemt_upstream_connect_attempt_total 167720
telemt_upstream_connect_success_total 167718
telemt_upstream_connect_attempts_per_request{bucket="1"} 167718
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 126270
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41414
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 1340
telemt_me_reconnect_attempts_total 129419
telemt_me_reconnect_success_total 129091
telemt_me_reader_eof_total 117034
telemt_me_idle_close_by_peer_total 117029
telemt_me_route_drop_no_conn_total 43264
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
telemt_pool_force_close_total 1236
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 117064
telemt_me_writer_restored_same_endpoint_total 129089
telemt_me_async_recovery_trigger_total 41934
telemt_user_connections_total{user="hello"} 112948
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 1580059416 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 38740040396 (36.08 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 26601.2 (7h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 245609
telemt_connections_bad_total 1273
telemt_handshake_timeouts_total 3609
telemt_upstream_connect_attempt_total 122008
telemt_upstream_connect_success_total 121808
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 121881
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41156
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 239
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 2399
telemt_me_reconnect_attempts_total 88761
telemt_me_reconnect_success_total 88683
telemt_me_reader_eof_total 90897
telemt_me_idle_close_by_peer_total 90892
telemt_me_route_drop_no_conn_total 92344
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 221
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
telemt_me_writer_removed_unexpected_total 91087
telemt_me_writer_restored_same_endpoint_total 88676
telemt_me_async_recovery_trigger_total 125587
telemt_me_writer_removed_unexpected_minus_restored_total 2411
telemt_user_connections_total{user="hello"} 229821
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 22063057632 (20.55 GB)
telemt_user_octets_to_client{user="hello"} 65265663240 (60.78 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 26601.5 (7h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 253221
telemt_connections_bad_total 75525
telemt_handshake_timeouts_total 16961
telemt_upstream_connect_attempt_total 49775
telemt_upstream_connect_success_total 49687
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 49728
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19948
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29703
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 961
telemt_me_reconnect_attempts_total 16726
telemt_me_reconnect_success_total 16696
telemt_me_reader_eof_total 22919
telemt_me_idle_close_by_peer_total 22917
telemt_me_route_drop_no_conn_total 67867
telemt_me_single_endpoint_shadow_rotate_total 224
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 223
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 123
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 81
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_pool_swap_total 13
telemt_pool_force_close_total 453
telemt_pool_stale_pick_total 474
telemt_me_writer_removed_unexpected_total 22924
telemt_me_writer_restored_same_endpoint_total 16691
telemt_me_writer_removed_unexpected_minus_restored_total 6233
telemt_user_connections_total{user="hello"} 156643
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 1755261660 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 50688363596 (47.21 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 26599.9 (7h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 215391
telemt_connections_bad_total 516
telemt_handshake_timeouts_total 2630
telemt_upstream_connect_attempt_total 44971
telemt_upstream_connect_success_total 44803
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 44823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17407
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27096
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 1232
telemt_me_reconnect_attempts_total 13458
telemt_me_reconnect_success_total 13423
telemt_me_reader_eof_total 18466
telemt_me_idle_close_by_peer_total 18464
telemt_me_route_drop_no_conn_total 71709
telemt_me_route_drop_channel_closed_total 4
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 220
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
telemt_me_writer_removed_unexpected_total 18535
telemt_me_writer_restored_same_endpoint_total 13415
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 5116
telemt_user_connections_total{user="hello"} 197802
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 10227944036 (9.53 GB)
telemt_user_octets_to_client{user="hello"} 69654441432 (64.87 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 17
```