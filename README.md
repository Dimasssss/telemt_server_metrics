# Server Metrics 2026-03-06 06:51:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 30590.2 (8h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 283748
telemt_connections_bad_total 16104
telemt_handshake_timeouts_total 3809
telemt_upstream_connect_attempt_total 30448
telemt_upstream_connect_success_total 30182
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 30182
telemt_upstream_connect_attempts_per_request{bucket="2"} 120
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11472
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 49
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_timeout_total 311
telemt_me_reconnect_attempts_total 10618
telemt_me_reconnect_success_total 10576
telemt_me_reader_eof_total 10934
telemt_me_idle_close_by_peer_total 10934
telemt_me_route_drop_no_conn_total 98082
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 127
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 959
telemt_desync_full_logged_total 291
telemt_desync_suppressed_total 668
telemt_desync_frames_bucket_total{bucket="1_2"} 250
telemt_desync_frames_bucket_total{bucket="3_10"} 336
telemt_desync_frames_bucket_total{bucket="gt_10"} 373
telemt_pool_swap_total 4
telemt_pool_force_close_total 208
telemt_me_writer_removed_unexpected_total 10936
telemt_me_writer_restored_same_endpoint_total 10570
telemt_me_writer_removed_unexpected_minus_restored_total 366
telemt_user_connections_total{user="hello"} 251571
telemt_user_connections_current{user="hello"} 799
telemt_user_octets_from_client{user="hello"} 8920372408 (8.31 GB)
telemt_user_octets_to_client{user="hello"} 92841480460 (86.47 GB)
telemt_user_unique_ips_current{user="hello"} 235
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 30585.6 (8h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121019
telemt_connections_bad_total 168
telemt_handshake_timeouts_total 12646
telemt_upstream_connect_attempt_total 25377
telemt_upstream_connect_success_total 25375
telemt_upstream_connect_attempts_per_request{bucket="1"} 25375
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14281
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11086
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 302
telemt_me_reconnect_attempts_total 6780
telemt_me_reconnect_success_total 6752
telemt_me_reader_eof_total 6903
telemt_me_idle_close_by_peer_total 6903
telemt_me_route_drop_no_conn_total 34380
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 129
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 391
telemt_desync_full_logged_total 127
telemt_desync_suppressed_total 264
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 146
telemt_desync_frames_bucket_total{bucket="gt_10"} 132
telemt_pool_swap_total 10
telemt_pool_force_close_total 197
telemt_pool_stale_pick_total 2124
telemt_me_writer_removed_unexpected_total 6904
telemt_me_writer_restored_same_endpoint_total 6745
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 105985
telemt_user_connections_current{user="hello"} 342
telemt_user_octets_from_client{user="hello"} 1229828732 (1.15 GB)
telemt_user_octets_to_client{user="hello"} 34947594252 (32.55 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 30583.0 (8h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 203042
telemt_connections_bad_total 1768
telemt_handshake_timeouts_total 5004
telemt_upstream_connect_attempt_total 35966
telemt_upstream_connect_success_total 35711
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 35711
telemt_upstream_connect_attempts_per_request{bucket="2"} 115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14423
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 500
telemt_me_reconnect_attempts_total 13859
telemt_me_reconnect_success_total 13819
telemt_me_reader_eof_total 14463
telemt_me_idle_close_by_peer_total 14461
telemt_me_route_drop_no_conn_total 61676
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 126
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 404
telemt_desync_full_logged_total 130
telemt_desync_suppressed_total 274
telemt_desync_frames_bucket_total{bucket="1_2"} 86
telemt_desync_frames_bucket_total{bucket="3_10"} 138
telemt_desync_frames_bucket_total{bucket="gt_10"} 180
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 14491
telemt_me_writer_restored_same_endpoint_total 13797
telemt_me_writer_restored_fallback_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 680
telemt_user_connections_total{user="hello"} 180651
telemt_user_connections_current{user="hello"} 489
telemt_user_octets_from_client{user="hello"} 1852484212 (1.73 GB)
telemt_user_octets_to_client{user="hello"} 59662106304 (55.56 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 30579.8 (8h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 163554
telemt_connections_bad_total 17317
telemt_handshake_timeouts_total 6533
telemt_upstream_connect_attempt_total 21797
telemt_upstream_connect_success_total 21724
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 21724
telemt_upstream_connect_attempts_per_request{bucket="2"} 35
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13000
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8722
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 233
telemt_me_reconnect_attempts_total 4886
telemt_me_reconnect_success_total 4853
telemt_me_reader_eof_total 5024
telemt_me_idle_close_by_peer_total 5024
telemt_me_route_drop_no_conn_total 52694
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 122
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 403
telemt_desync_full_logged_total 126
telemt_desync_suppressed_total 277
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 152
telemt_desync_frames_bucket_total{bucket="gt_10"} 172
telemt_pool_swap_total 10
telemt_pool_force_close_total 244
telemt_me_writer_removed_unexpected_total 5025
telemt_me_writer_restored_same_endpoint_total 4846
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 133315
telemt_user_connections_current{user="hello"} 352
telemt_user_octets_from_client{user="hello"} 1924917692 (1.79 GB)
telemt_user_octets_to_client{user="hello"} 44672278560 (41.60 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 30578.6 (8h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176634
telemt_connections_bad_total 3278
telemt_handshake_timeouts_total 1023
telemt_upstream_connect_attempt_total 20729
telemt_upstream_connect_success_total 20682
telemt_upstream_connect_attempts_per_request{bucket="1"} 20682
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8350
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 318
telemt_me_reconnect_attempts_total 3703
telemt_me_reconnect_success_total 3686
telemt_me_reader_eof_total 3804
telemt_me_idle_close_by_peer_total 3803
telemt_me_route_drop_no_conn_total 67404
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 129
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 380
telemt_desync_full_logged_total 157
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 183
telemt_desync_frames_bucket_total{bucket="gt_10"} 134
telemt_pool_swap_total 10
telemt_pool_force_close_total 208
telemt_pool_stale_pick_total 5
telemt_me_writer_removed_unexpected_total 3819
telemt_me_writer_restored_same_endpoint_total 3679
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 169018
telemt_user_connections_current{user="hello"} 489
telemt_user_octets_from_client{user="hello"} 24335242592 (22.66 GB)
telemt_user_octets_to_client{user="hello"} 103201026480 (96.11 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 99
```