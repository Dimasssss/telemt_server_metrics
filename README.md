# Server Metrics 2026-03-07 02:17:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 29374.1 (8h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 330412
telemt_connections_bad_total 3894
telemt_handshake_timeouts_total 9604
telemt_upstream_connect_attempt_total 97186
telemt_upstream_connect_success_total 94309
telemt_upstream_connect_fail_total 2732
telemt_upstream_connect_attempts_per_request{bucket="1"} 97041
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35805
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 58224
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 112
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 168
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2732
telemt_me_keepalive_timeout_total 1989
telemt_me_reconnect_attempts_total 60712
telemt_me_reconnect_success_total 58072
telemt_me_reader_eof_total 60394
telemt_me_idle_close_by_peer_total 60391
telemt_me_route_drop_no_conn_total 123849
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 241
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1119
telemt_desync_full_logged_total 308
telemt_desync_suppressed_total 811
telemt_desync_frames_bucket_total{bucket="1_2"} 302
telemt_desync_frames_bucket_total{bucket="3_10"} 503
telemt_desync_frames_bucket_total{bucket="gt_10"} 314
telemt_pool_swap_total 14
telemt_pool_force_close_total 627
telemt_pool_stale_pick_total 187
telemt_me_writer_removed_unexpected_total 60507
telemt_me_writer_restored_same_endpoint_total 57905
telemt_me_writer_restored_fallback_total 161
telemt_me_async_recovery_trigger_total 52970
telemt_me_writer_removed_unexpected_minus_restored_total 2441
telemt_user_connections_total{user="hello"} 300809
telemt_user_connections_current{user="hello"} 309
telemt_user_octets_from_client{user="hello"} 4443858016 (4.14 GB)
telemt_user_octets_to_client{user="hello"} 129978514748 (121.05 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 29374.0 (8h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145054
telemt_connections_bad_total 125
telemt_handshake_timeouts_total 19641
telemt_upstream_connect_attempt_total 200914
telemt_upstream_connect_success_total 200912
telemt_upstream_connect_attempts_per_request{bucket="1"} 200912
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155021
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45856
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 1538
telemt_me_reconnect_attempts_total 158365
telemt_me_reconnect_success_total 157910
telemt_me_reader_eof_total 142566
telemt_me_idle_close_by_peer_total 142561
telemt_me_route_drop_no_conn_total 44450
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 255
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 835
telemt_desync_full_logged_total 224
telemt_desync_suppressed_total 611
telemt_desync_frames_bucket_total{bucket="1_2"} 151
telemt_desync_frames_bucket_total{bucket="3_10"} 414
telemt_desync_frames_bucket_total{bucket="gt_10"} 270
telemt_pool_swap_total 22
telemt_pool_force_close_total 1440
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 142607
telemt_me_writer_restored_same_endpoint_total 157908
telemt_me_async_recovery_trigger_total 52963
telemt_user_connections_total{user="hello"} 118161
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 1602421420 (1.49 GB)
telemt_user_octets_to_client{user="hello"} 39938163216 (37.20 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 29374.0 (8h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 257776
telemt_connections_bad_total 1456
telemt_handshake_timeouts_total 4361
telemt_upstream_connect_attempt_total 152531
telemt_upstream_connect_success_total 152304
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 152388
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 103922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 48085
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 292
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 2734
telemt_me_reconnect_attempts_total 115455
telemt_me_reconnect_success_total 115364
telemt_me_reader_eof_total 117099
telemt_me_idle_close_by_peer_total 117094
telemt_me_route_drop_no_conn_total 94633
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
telemt_me_writer_removed_unexpected_total 117290
telemt_me_writer_restored_same_endpoint_total 115357
telemt_me_async_recovery_trigger_total 158635
telemt_me_writer_removed_unexpected_minus_restored_total 1933
telemt_user_connections_total{user="hello"} 240913
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 23608287372 (21.99 GB)
telemt_user_octets_to_client{user="hello"} 67834815160 (63.18 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 29374.3 (8h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 267296
telemt_connections_bad_total 82918
telemt_handshake_timeouts_total 17332
telemt_upstream_connect_attempt_total 57819
telemt_upstream_connect_success_total 57729
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 57772
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23567
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34125
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 1098
telemt_me_reconnect_attempts_total 20566
telemt_me_reconnect_success_total 20534
telemt_me_reader_eof_total 27881
telemt_me_idle_close_by_peer_total 27879
telemt_me_route_drop_no_conn_total 72475
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
telemt_me_writer_removed_unexpected_total 27886
telemt_me_writer_restored_same_endpoint_total 20529
telemt_me_writer_removed_unexpected_minus_restored_total 7357
telemt_user_connections_total{user="hello"} 162809
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 1798540496 (1.68 GB)
telemt_user_octets_to_client{user="hello"} 51484351284 (47.95 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 29372.6 (8h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 224492
telemt_connections_bad_total 517
telemt_handshake_timeouts_total 2907
telemt_upstream_connect_attempt_total 49721
telemt_upstream_connect_success_total 49534
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 49558
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19019
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30154
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 350
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 1327
telemt_me_reconnect_attempts_total 14534
telemt_me_reconnect_success_total 14493
telemt_me_reader_eof_total 19977
telemt_me_idle_close_by_peer_total 19975
telemt_me_route_drop_no_conn_total 73781
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
telemt_me_writer_removed_unexpected_total 20046
telemt_me_writer_restored_same_endpoint_total 14485
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 5557
telemt_user_connections_total{user="hello"} 206221
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 10302419844 (9.59 GB)
telemt_user_octets_to_client{user="hello"} 75523393436 (70.34 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 28
```