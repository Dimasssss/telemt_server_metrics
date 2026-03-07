# Server Metrics 2026-03-07 01:00:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 24752.3 (6h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 308197
telemt_connections_bad_total 3690
telemt_handshake_timeouts_total 9413
telemt_upstream_connect_attempt_total 72357
telemt_upstream_connect_success_total 70377
telemt_upstream_connect_fail_total 1844
telemt_upstream_connect_attempts_per_request{bucket="1"} 72221
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25898
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44243
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 90
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1844
telemt_me_keepalive_timeout_total 1654
telemt_me_reconnect_attempts_total 42089
telemt_me_reconnect_success_total 40307
telemt_me_reader_eof_total 42705
telemt_me_idle_close_by_peer_total 42705
telemt_me_route_drop_no_conn_total 117413
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 202
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1008
telemt_desync_full_logged_total 274
telemt_desync_suppressed_total 734
telemt_desync_frames_bucket_total{bucket="1_2"} 279
telemt_desync_frames_bucket_total{bucket="3_10"} 454
telemt_desync_frames_bucket_total{bucket="gt_10"} 275
telemt_pool_swap_total 11
telemt_pool_force_close_total 540
telemt_pool_stale_pick_total 187
telemt_me_writer_removed_unexpected_total 42818
telemt_me_writer_restored_same_endpoint_total 40193
telemt_me_writer_restored_fallback_total 108
telemt_me_async_recovery_trigger_total 34587
telemt_me_writer_removed_unexpected_minus_restored_total 2517
telemt_user_connections_total{user="hello"} 279813
telemt_user_connections_current{user="hello"} 361
telemt_user_octets_from_client{user="hello"} 4260002132 (3.97 GB)
telemt_user_octets_to_client{user="hello"} 122048570692 (113.67 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 24752.2 (6h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132258
telemt_connections_bad_total 118
telemt_handshake_timeouts_total 15981
telemt_upstream_connect_attempt_total 142868
telemt_upstream_connect_success_total 142866
telemt_upstream_connect_attempts_per_request{bucket="1"} 142866
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 105057
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37776
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 1227
telemt_me_reconnect_attempts_total 107734
telemt_me_reconnect_success_total 107450
telemt_me_reader_eof_total 97988
telemt_me_idle_close_by_peer_total 97983
telemt_me_route_drop_no_conn_total 42403
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 215
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 809
telemt_desync_full_logged_total 214
telemt_desync_suppressed_total 595
telemt_desync_frames_bucket_total{bucket="1_2"} 140
telemt_desync_frames_bucket_total{bucket="3_10"} 407
telemt_desync_frames_bucket_total{bucket="gt_10"} 262
telemt_pool_swap_total 17
telemt_pool_force_close_total 1102
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 98017
telemt_me_writer_restored_same_endpoint_total 107448
telemt_me_async_recovery_trigger_total 34580
telemt_user_connections_total{user="hello"} 109640
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 1566483368 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 37780075812 (35.19 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 24752.1 (6h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 238173
telemt_connections_bad_total 1243
telemt_handshake_timeouts_total 3589
telemt_upstream_connect_attempt_total 107198
telemt_upstream_connect_success_total 107022
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 107087
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70298
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36540
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 180
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 2159
telemt_me_reconnect_attempts_total 76763
telemt_me_reconnect_success_total 76696
telemt_me_reader_eof_total 78225
telemt_me_idle_close_by_peer_total 78220
telemt_me_route_drop_no_conn_total 89663
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 205
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1045
telemt_desync_full_logged_total 267
telemt_desync_suppressed_total 778
telemt_desync_frames_bucket_total{bucket="1_2"} 198
telemt_desync_frames_bucket_total{bucket="3_10"} 429
telemt_desync_frames_bucket_total{bucket="gt_10"} 418
telemt_pool_swap_total 14
telemt_pool_force_close_total 372
telemt_pool_stale_pick_total 126
telemt_me_writer_removed_unexpected_total 78393
telemt_me_writer_restored_same_endpoint_total 76689
telemt_me_async_recovery_trigger_total 103535
telemt_me_writer_removed_unexpected_minus_restored_total 1704
telemt_user_connections_total{user="hello"} 222522
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 20339164496 (18.94 GB)
telemt_user_octets_to_client{user="hello"} 63714678436 (59.34 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 24752.6 (6h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 242778
telemt_connections_bad_total 69596
telemt_handshake_timeouts_total 16938
telemt_upstream_connect_attempt_total 44221
telemt_upstream_connect_success_total 44136
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 44174
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17877
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26225
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 857
telemt_me_reconnect_attempts_total 14156
telemt_me_reconnect_success_total 14129
telemt_me_reader_eof_total 19264
telemt_me_idle_close_by_peer_total 19262
telemt_me_route_drop_no_conn_total 64847
telemt_me_single_endpoint_shadow_rotate_total 208
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 218
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 122
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 79
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 13
telemt_pool_force_close_total 453
telemt_pool_stale_pick_total 474
telemt_me_writer_removed_unexpected_total 19269
telemt_me_writer_restored_same_endpoint_total 14124
telemt_me_writer_removed_unexpected_minus_restored_total 5145
telemt_user_connections_total{user="hello"} 152231
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 1735438772 (1.62 GB)
telemt_user_octets_to_client{user="hello"} 49541780216 (46.14 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 24751.0 (6h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 209128
telemt_connections_bad_total 510
telemt_handshake_timeouts_total 2450
telemt_upstream_connect_attempt_total 41054
telemt_upstream_connect_success_total 40901
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 40920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15996
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24654
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 242
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 1142
telemt_me_reconnect_attempts_total 12111
telemt_me_reconnect_success_total 12078
telemt_me_reader_eof_total 16506
telemt_me_idle_close_by_peer_total 16504
telemt_me_route_drop_no_conn_total 69875
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 204
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 799
telemt_desync_full_logged_total 206
telemt_desync_suppressed_total 593
telemt_desync_frames_bucket_total{bucket="1_2"} 273
telemt_desync_frames_bucket_total{bucket="3_10"} 263
telemt_desync_frames_bucket_total{bucket="gt_10"} 263
telemt_pool_swap_total 14
telemt_pool_force_close_total 428
telemt_pool_stale_pick_total 215
telemt_me_writer_removed_unexpected_total 16572
telemt_me_writer_restored_same_endpoint_total 12074
telemt_me_writer_removed_unexpected_minus_restored_total 4498
telemt_user_connections_total{user="hello"} 191886
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 10164885916 (9.47 GB)
telemt_user_octets_to_client{user="hello"} 67733958296 (63.08 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 34
```