# Server Metrics 2026-03-06 08:08:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 35201.0 (9h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 379678
telemt_connections_bad_total 17022
telemt_handshake_timeouts_total 4139
telemt_upstream_connect_attempt_total 36126
telemt_upstream_connect_success_total 35772
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 35772
telemt_upstream_connect_attempts_per_request{bucket="2"} 159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21944
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13725
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 70
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_keepalive_timeout_total 379
telemt_me_reconnect_attempts_total 13073
telemt_me_reconnect_success_total 13022
telemt_me_reader_eof_total 13476
telemt_me_idle_close_by_peer_total 13476
telemt_me_route_drop_no_conn_total 134796
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 145
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1277
telemt_desync_full_logged_total 401
telemt_desync_suppressed_total 876
telemt_desync_frames_bucket_total{bucket="1_2"} 364
telemt_desync_frames_bucket_total{bucket="3_10"} 428
telemt_desync_frames_bucket_total{bucket="gt_10"} 485
telemt_pool_swap_total 5
telemt_pool_force_close_total 281
telemt_me_writer_removed_unexpected_total 13479
telemt_me_writer_restored_same_endpoint_total 13014
telemt_me_writer_removed_unexpected_minus_restored_total 465
telemt_user_connections_total{user="hello"} 337591
telemt_user_connections_current{user="hello"} 928
telemt_user_octets_from_client{user="hello"} 10509536196 (9.79 GB)
telemt_user_octets_to_client{user="hello"} 120714125356 (112.42 GB)
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 35196.4 (9h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 168384
telemt_connections_bad_total 312
telemt_handshake_timeouts_total 18359
telemt_upstream_connect_attempt_total 27428
telemt_upstream_connect_success_total 27426
telemt_upstream_connect_attempts_per_request{bucket="1"} 27426
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12159
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 330
telemt_me_reconnect_attempts_total 6828
telemt_me_reconnect_success_total 6795
telemt_me_reader_eof_total 6947
telemt_me_idle_close_by_peer_total 6947
telemt_me_route_drop_no_conn_total 50629
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 150
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 498
telemt_desync_full_logged_total 166
telemt_desync_suppressed_total 332
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 185
telemt_desync_frames_bucket_total{bucket="gt_10"} 169
telemt_pool_swap_total 12
telemt_pool_force_close_total 238
telemt_pool_stale_pick_total 2124
telemt_me_writer_removed_unexpected_total 6948
telemt_me_writer_restored_same_endpoint_total 6788
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 146639
telemt_user_connections_current{user="hello"} 413
telemt_user_octets_from_client{user="hello"} 1701327160 (1.58 GB)
telemt_user_octets_to_client{user="hello"} 46432106568 (43.24 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 35193.7 (9h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 296131
telemt_connections_bad_total 2066
telemt_handshake_timeouts_total 11584
telemt_upstream_connect_attempt_total 38249
telemt_upstream_connect_success_total 37958
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 37958
telemt_upstream_connect_attempts_per_request{bucket="2"} 131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15444
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_timeout_total 546
telemt_me_reconnect_attempts_total 14297
telemt_me_reconnect_success_total 14253
telemt_me_reader_eof_total 14907
telemt_me_idle_close_by_peer_total 14905
telemt_me_route_drop_no_conn_total 93237
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 142
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 800
telemt_desync_full_logged_total 242
telemt_desync_suppressed_total 558
telemt_desync_frames_bucket_total{bucket="1_2"} 156
telemt_desync_frames_bucket_total{bucket="3_10"} 292
telemt_desync_frames_bucket_total{bucket="gt_10"} 352
telemt_pool_swap_total 5
telemt_pool_force_close_total 173
telemt_pool_stale_pick_total 227
telemt_me_writer_removed_unexpected_total 14936
telemt_me_writer_restored_same_endpoint_total 14231
telemt_me_writer_restored_fallback_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 691
telemt_user_connections_total{user="hello"} 256395
telemt_user_connections_current{user="hello"} 593
telemt_user_octets_from_client{user="hello"} 2949695512 (2.75 GB)
telemt_user_octets_to_client{user="hello"} 80702920284 (75.16 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 35190.5 (9h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 223504
telemt_connections_bad_total 31775
telemt_handshake_timeouts_total 11674
telemt_upstream_connect_attempt_total 23912
telemt_upstream_connect_success_total 23821
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 23821
telemt_upstream_connect_attempts_per_request{bucket="2"} 43
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9436
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 262
telemt_me_reconnect_attempts_total 5050
telemt_me_reconnect_success_total 5014
telemt_me_reader_eof_total 5186
telemt_me_idle_close_by_peer_total 5186
telemt_me_route_drop_no_conn_total 66856
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 140
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 537
telemt_desync_full_logged_total 182
telemt_desync_suppressed_total 355
telemt_desync_frames_bucket_total{bucket="1_2"} 102
telemt_desync_frames_bucket_total{bucket="3_10"} 198
telemt_desync_frames_bucket_total{bucket="gt_10"} 237
telemt_pool_swap_total 12
telemt_pool_force_close_total 287
telemt_me_writer_removed_unexpected_total 5187
telemt_me_writer_restored_same_endpoint_total 5006
telemt_me_writer_removed_unexpected_minus_restored_total 181
telemt_user_connections_total{user="hello"} 172201
telemt_user_connections_current{user="hello"} 400
telemt_user_octets_from_client{user="hello"} 2350469164 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 58137009732 (54.14 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 35189.4 (9h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 235180
telemt_connections_bad_total 3311
telemt_handshake_timeouts_total 1290
telemt_upstream_connect_attempt_total 24062
telemt_upstream_connect_success_total 24007
telemt_upstream_connect_attempts_per_request{bucket="1"} 24007
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9745
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_timeout_total 369
telemt_me_reconnect_attempts_total 4509
telemt_me_reconnect_success_total 4488
telemt_me_reader_eof_total 4632
telemt_me_idle_close_by_peer_total 4631
telemt_me_route_drop_no_conn_total 98244
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 150
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 510
telemt_desync_full_logged_total 202
telemt_desync_suppressed_total 308
telemt_desync_frames_bucket_total{bucket="1_2"} 109
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 175
telemt_pool_swap_total 11
telemt_pool_force_close_total 208
telemt_pool_stale_pick_total 5
telemt_me_writer_removed_unexpected_total 4647
telemt_me_writer_restored_same_endpoint_total 4481
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 224192
telemt_user_connections_current{user="hello"} 548
telemt_user_octets_from_client{user="hello"} 24980077792 (23.26 GB)
telemt_user_octets_to_client{user="hello"} 130938215144 (121.95 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 77
```