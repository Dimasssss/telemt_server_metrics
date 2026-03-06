# Server Metrics 2026-03-06 07:11:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 31819.4 (8h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 312757
telemt_connections_bad_total 16144
telemt_handshake_timeouts_total 3908
telemt_upstream_connect_attempt_total 31821
telemt_upstream_connect_success_total 31505
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 31505
telemt_upstream_connect_attempts_per_request{bucket="2"} 141
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19382
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12043
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 55
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_timeout_total 326
telemt_me_reconnect_attempts_total 11034
telemt_me_reconnect_success_total 10988
telemt_me_reader_eof_total 11368
telemt_me_idle_close_by_peer_total 11368
telemt_me_route_drop_no_conn_total 108705
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 133
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1056
telemt_desync_full_logged_total 323
telemt_desync_suppressed_total 733
telemt_desync_frames_bucket_total{bucket="1_2"} 290
telemt_desync_frames_bucket_total{bucket="3_10"} 350
telemt_desync_frames_bucket_total{bucket="gt_10"} 416
telemt_pool_swap_total 4
telemt_pool_force_close_total 208
telemt_me_writer_removed_unexpected_total 11370
telemt_me_writer_restored_same_endpoint_total 10982
telemt_me_writer_removed_unexpected_minus_restored_total 388
telemt_user_connections_total{user="hello"} 274259
telemt_user_connections_current{user="hello"} 982
telemt_user_octets_from_client{user="hello"} 9426817352 (8.78 GB)
telemt_user_octets_to_client{user="hello"} 99864406516 (93.01 GB)
telemt_user_unique_ips_current{user="hello"} 285
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 31814.9 (8h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132875
telemt_connections_bad_total 179
telemt_handshake_timeouts_total 14251
telemt_upstream_connect_attempt_total 25991
telemt_upstream_connect_success_total 25989
telemt_upstream_connect_attempts_per_request{bucket="1"} 25989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14595
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11386
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 313
telemt_me_reconnect_attempts_total 6795
telemt_me_reconnect_success_total 6765
telemt_me_reader_eof_total 6916
telemt_me_idle_close_by_peer_total 6916
telemt_me_route_drop_no_conn_total 39705
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 137
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 425
telemt_desync_full_logged_total 140
telemt_desync_suppressed_total 285
telemt_desync_frames_bucket_total{bucket="1_2"} 121
telemt_desync_frames_bucket_total{bucket="3_10"} 158
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 11
telemt_pool_force_close_total 238
telemt_pool_stale_pick_total 2124
telemt_me_writer_removed_unexpected_total 6917
telemt_me_writer_restored_same_endpoint_total 6758
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 116013
telemt_user_connections_current{user="hello"} 345
telemt_user_octets_from_client{user="hello"} 1308245688 (1.22 GB)
telemt_user_octets_to_client{user="hello"} 37228718956 (34.67 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 31812.2 (8h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 231901
telemt_connections_bad_total 1790
telemt_handshake_timeouts_total 6675
telemt_upstream_connect_attempt_total 36493
telemt_upstream_connect_success_total 36220
telemt_upstream_connect_fail_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 36220
telemt_upstream_connect_attempts_per_request{bucket="2"} 124
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14641
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 124
telemt_me_keepalive_timeout_total 516
telemt_me_reconnect_attempts_total 14112
telemt_me_reconnect_success_total 14072
telemt_me_reader_eof_total 14725
telemt_me_idle_close_by_peer_total 14723
telemt_me_route_drop_no_conn_total 69239
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 130
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 449
telemt_desync_full_logged_total 150
telemt_desync_suppressed_total 299
telemt_desync_frames_bucket_total{bucket="1_2"} 94
telemt_desync_frames_bucket_total{bucket="3_10"} 158
telemt_desync_frames_bucket_total{bucket="gt_10"} 197
telemt_pool_swap_total 5
telemt_pool_force_close_total 173
telemt_pool_stale_pick_total 208
telemt_me_writer_removed_unexpected_total 14753
telemt_me_writer_restored_same_endpoint_total 14050
telemt_me_writer_restored_fallback_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 689
telemt_user_connections_total{user="hello"} 205836
telemt_user_connections_current{user="hello"} 599
telemt_user_octets_from_client{user="hello"} 2076463432 (1.93 GB)
telemt_user_octets_to_client{user="hello"} 65658564940 (61.15 GB)
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 31808.9 (8h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 178703
telemt_connections_bad_total 21251
telemt_handshake_timeouts_total 7134
telemt_upstream_connect_attempt_total 22408
telemt_upstream_connect_success_total 22329
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 22329
telemt_upstream_connect_attempts_per_request{bucket="2"} 38
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8924
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 242
telemt_me_reconnect_attempts_total 4919
telemt_me_reconnect_success_total 4886
telemt_me_reader_eof_total 5057
telemt_me_idle_close_by_peer_total 5057
telemt_me_route_drop_no_conn_total 56828
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 130
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 424
telemt_desync_full_logged_total 135
telemt_desync_suppressed_total 289
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 159
telemt_desync_frames_bucket_total{bucket="gt_10"} 185
telemt_pool_swap_total 10
telemt_pool_force_close_total 244
telemt_me_writer_removed_unexpected_total 5058
telemt_me_writer_restored_same_endpoint_total 4879
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 143518
telemt_user_connections_current{user="hello"} 344
telemt_user_octets_from_client{user="hello"} 2049836048 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 49444298776 (46.05 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 31808.0 (8h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 192232
telemt_connections_bad_total 3279
telemt_handshake_timeouts_total 1089
telemt_upstream_connect_attempt_total 21299
telemt_upstream_connect_success_total 21251
telemt_upstream_connect_attempts_per_request{bucket="1"} 21251
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12550
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8600
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 327
telemt_me_reconnect_attempts_total 3721
telemt_me_reconnect_success_total 3703
telemt_me_reader_eof_total 3821
telemt_me_idle_close_by_peer_total 3820
telemt_me_route_drop_no_conn_total 76934
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 137
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 425
telemt_desync_full_logged_total 170
telemt_desync_suppressed_total 255
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 200
telemt_desync_frames_bucket_total{bucket="gt_10"} 151
telemt_pool_swap_total 10
telemt_pool_force_close_total 208
telemt_pool_stale_pick_total 5
telemt_me_writer_removed_unexpected_total 3836
telemt_me_writer_restored_same_endpoint_total 3696
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 184230
telemt_user_connections_current{user="hello"} 499
telemt_user_octets_from_client{user="hello"} 24455867064 (22.78 GB)
telemt_user_octets_to_client{user="hello"} 111207915496 (103.57 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 87
```