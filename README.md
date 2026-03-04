# Server Metrics 2026-03-04 07:26:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 36947.3 (10h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 399274
telemt_connections_bad_total 6418
telemt_handshake_timeouts_total 5919
telemt_upstream_connect_attempt_total 23671
telemt_upstream_connect_success_total 23560
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 23560
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10165
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 249
telemt_me_reconnect_attempts_total 4763
telemt_me_reconnect_success_total 4735
telemt_me_reader_eof_total 4845
telemt_me_idle_close_by_peer_total 4845
telemt_me_route_drop_no_conn_total 130585
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 146
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 768
telemt_desync_full_logged_total 290
telemt_desync_suppressed_total 478
telemt_desync_frames_bucket_total{bucket="1_2"} 227
telemt_desync_frames_bucket_total{bucket="3_10"} 269
telemt_desync_frames_bucket_total{bucket="gt_10"} 272
telemt_pool_swap_total 8
telemt_pool_force_close_total 300
telemt_me_writer_removed_unexpected_total 4845
telemt_me_writer_restored_same_endpoint_total 4715
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 331767
telemt_user_connections_current{user="hello"} 865
telemt_user_octets_from_client{user="hello"} 3891324840 (3.62 GB)
telemt_user_octets_to_client{user="hello"} 100730349132 (93.81 GB)
telemt_user_unique_ips_current{user="hello"} 99
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 36943.8 (10h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 169056
telemt_connections_bad_total 1367
telemt_handshake_timeouts_total 23096
telemt_upstream_connect_attempt_total 75705
telemt_upstream_connect_success_total 74601
telemt_upstream_connect_fail_total 514
telemt_upstream_connect_attempts_per_request{bucket="1"} 74595
telemt_upstream_connect_attempts_per_request{bucket="2"} 520
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50549
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24030
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 514
telemt_me_keepalive_timeout_total 1183
telemt_me_reconnect_attempts_total 44201
telemt_me_reconnect_success_total 44125
telemt_me_reader_eof_total 45214
telemt_me_idle_close_by_peer_total 45213
telemt_me_route_drop_no_conn_total 61686
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 158
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 317
telemt_desync_full_logged_total 110
telemt_desync_suppressed_total 207
telemt_desync_frames_bucket_total{bucket="1_2"} 71
telemt_desync_frames_bucket_total{bucket="3_10"} 162
telemt_desync_frames_bucket_total{bucket="gt_10"} 84
telemt_pool_swap_total 2
telemt_pool_force_close_total 138
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 45294
telemt_me_writer_restored_same_endpoint_total 44100
telemt_me_writer_removed_unexpected_minus_restored_total 1194
telemt_user_connections_total{user="hello"} 117746
telemt_user_connections_current{user="hello"} 365
telemt_user_octets_from_client{user="hello"} 1270684732 (1.18 GB)
telemt_user_octets_to_client{user="hello"} 46634547928 (43.43 GB)
telemt_user_unique_ips_current{user="hello"} 35
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 36942.6 (10h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 335340
telemt_connections_bad_total 104378
telemt_handshake_timeouts_total 9921
telemt_upstream_connect_attempt_total 54652
telemt_upstream_connect_success_total 54329
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 54328
telemt_upstream_connect_attempts_per_request{bucket="2"} 153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23002
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_keepalive_timeout_total 718
telemt_me_reconnect_attempts_total 24450
telemt_me_reconnect_success_total 24386
telemt_me_reader_eof_total 25718
telemt_me_idle_close_by_peer_total 25715
telemt_me_route_drop_no_conn_total 96955
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 155
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 520
telemt_desync_full_logged_total 194
telemt_desync_suppressed_total 326
telemt_desync_frames_bucket_total{bucket="1_2"} 139
telemt_desync_frames_bucket_total{bucket="3_10"} 192
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 25729
telemt_me_writer_restored_same_endpoint_total 24365
telemt_me_writer_removed_unexpected_minus_restored_total 1364
telemt_user_connections_total{user="hello"} 211942
telemt_user_connections_current{user="hello"} 460
telemt_user_octets_from_client{user="hello"} 1903927852 (1.77 GB)
telemt_user_octets_to_client{user="hello"} 74895027204 (69.75 GB)
telemt_user_unique_ips_current{user="hello"} 47
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 36941.5 (10h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 192671
telemt_connections_bad_total 15360
telemt_handshake_timeouts_total 7369
telemt_upstream_connect_attempt_total 28148
telemt_upstream_connect_success_total 28029
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 28029
telemt_upstream_connect_attempts_per_request{bucket="2"} 58
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17368
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10660
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 312
telemt_me_reconnect_attempts_total 6076
telemt_me_reconnect_success_total 6062
telemt_me_reader_eof_total 6178
telemt_me_idle_close_by_peer_total 6178
telemt_me_route_drop_no_conn_total 60723
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 153
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 10
telemt_pool_force_close_total 232
telemt_me_writer_removed_unexpected_total 6178
telemt_me_writer_restored_same_endpoint_total 6041
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 151231
telemt_user_connections_current{user="hello"} 273
telemt_user_octets_from_client{user="hello"} 1582936428 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 54599911100 (50.85 GB)
telemt_user_unique_ips_current{user="hello"} 37
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 36940.1 (10h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 334437
telemt_connections_bad_total 6421
telemt_handshake_timeouts_total 129521
telemt_upstream_connect_attempt_total 51997
telemt_upstream_connect_success_total 51647
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 51647
telemt_upstream_connect_attempts_per_request{bucket="2"} 162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30889
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20620
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_keepalive_timeout_total 703
telemt_me_reconnect_attempts_total 23925
telemt_me_reconnect_success_total 23909
telemt_me_reader_eof_total 25183
telemt_me_idle_close_by_peer_total 25182
telemt_me_route_drop_no_conn_total 90405
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_shadow_rotate_total 156
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 229
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 117
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 25196
telemt_me_writer_restored_same_endpoint_total 23884
telemt_me_writer_removed_unexpected_minus_restored_total 1312
telemt_user_connections_total{user="hello"} 192118
telemt_user_connections_current{user="hello"} 301
telemt_user_octets_from_client{user="hello"} 2481457636 (2.31 GB)
telemt_user_octets_to_client{user="hello"} 42778270200 (39.84 GB)
telemt_user_unique_ips_current{user="hello"} 35
```