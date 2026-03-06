# Server Metrics 2026-03-06 22:31:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 15819.9 (4h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 256063
telemt_connections_bad_total 2243
telemt_handshake_timeouts_total 9143
telemt_upstream_connect_attempt_total 25776
telemt_upstream_connect_success_total 25577
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 25649
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8285
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17131
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 61
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 1087
telemt_me_reconnect_attempts_total 7869
telemt_me_reconnect_success_total 7830
telemt_me_reader_eof_total 10307
telemt_me_idle_close_by_peer_total 10307
telemt_me_route_drop_no_conn_total 97990
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 131
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 824
telemt_desync_full_logged_total 241
telemt_desync_suppressed_total 583
telemt_desync_frames_bucket_total{bucket="1_2"} 240
telemt_desync_frames_bucket_total{bucket="3_10"} 330
telemt_desync_frames_bucket_total{bucket="gt_10"} 254
telemt_pool_swap_total 5
telemt_pool_force_close_total 320
telemt_pool_stale_pick_total 168
telemt_me_writer_removed_unexpected_total 10415
telemt_me_writer_restored_same_endpoint_total 7824
telemt_me_writer_removed_unexpected_minus_restored_total 2591
telemt_user_connections_total{user="hello"} 230859
telemt_user_connections_current{user="hello"} 424
telemt_user_octets_from_client{user="hello"} 3596205668 (3.35 GB)
telemt_user_octets_to_client{user="hello"} 96282995488 (89.67 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 15819.8 (4h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103679
telemt_connections_bad_total 97
telemt_handshake_timeouts_total 8811
telemt_upstream_connect_attempt_total 31250
telemt_upstream_connect_success_total 31249
telemt_upstream_connect_attempts_per_request{bucket="1"} 31249
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22495
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 516
telemt_me_reconnect_attempts_total 10861
telemt_me_reconnect_success_total 10846
telemt_me_reader_eof_total 15222
telemt_me_idle_close_by_peer_total 15219
telemt_me_route_drop_no_conn_total 37056
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 135
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 667
telemt_desync_full_logged_total 177
telemt_desync_suppressed_total 490
telemt_desync_frames_bucket_total{bucket="1_2"} 111
telemt_desync_frames_bucket_total{bucket="3_10"} 311
telemt_desync_frames_bucket_total{bucket="gt_10"} 245
telemt_pool_swap_total 7
telemt_pool_force_close_total 299
telemt_pool_stale_pick_total 37
telemt_me_writer_removed_unexpected_total 15222
telemt_me_writer_restored_same_endpoint_total 10844
telemt_me_writer_removed_unexpected_minus_restored_total 4378
telemt_user_connections_total{user="hello"} 89290
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 1343037612 (1.25 GB)
telemt_user_octets_to_client{user="hello"} 30565126928 (28.47 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 15819.7 (4h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 199344
telemt_connections_bad_total 840
telemt_handshake_timeouts_total 3226
telemt_upstream_connect_attempt_total 24935
telemt_upstream_connect_success_total 24786
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 24829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10355
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14304
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 1095
telemt_me_reconnect_attempts_total 7177
telemt_me_reconnect_success_total 7146
telemt_me_reader_eof_total 9608
telemt_me_idle_close_by_peer_total 9605
telemt_me_route_drop_no_conn_total 74982
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 132
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 906
telemt_desync_full_logged_total 222
telemt_desync_suppressed_total 684
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 368
telemt_desync_frames_bucket_total{bucket="gt_10"} 369
telemt_pool_swap_total 8
telemt_pool_force_close_total 276
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 9713
telemt_me_writer_restored_same_endpoint_total 7139
telemt_me_writer_removed_unexpected_minus_restored_total 2574
telemt_user_connections_total{user="hello"} 184863
telemt_user_connections_current{user="hello"} 286
telemt_user_octets_from_client{user="hello"} 12879730996 (12.00 GB)
telemt_user_octets_to_client{user="hello"} 56200673736 (52.34 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 15820.3 (4h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 198319
telemt_connections_bad_total 54196
telemt_handshake_timeouts_total 15936
telemt_upstream_connect_attempt_total 26811
telemt_upstream_connect_success_total 26738
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 26764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15078
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 524
telemt_me_reconnect_attempts_total 8752
telemt_me_reconnect_success_total 8734
telemt_me_reader_eof_total 11736
telemt_me_idle_close_by_peer_total 11735
telemt_me_route_drop_no_conn_total 50641
telemt_me_single_endpoint_shadow_rotate_total 132
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 63
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 8
telemt_pool_force_close_total 307
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 11741
telemt_me_writer_restored_same_endpoint_total 8729
telemt_me_writer_removed_unexpected_minus_restored_total 3012
telemt_user_connections_total{user="hello"} 124797
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 1617730640 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 38777629544 (36.11 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 15818.6 (4h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 171782
telemt_connections_bad_total 459
telemt_handshake_timeouts_total 1287
telemt_upstream_connect_attempt_total 24029
telemt_upstream_connect_success_total 23898
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 23917
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14172
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 170
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 820
telemt_me_reconnect_attempts_total 7088
telemt_me_reconnect_success_total 7059
telemt_me_reader_eof_total 9552
telemt_me_idle_close_by_peer_total 9551
telemt_me_route_drop_no_conn_total 59595
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 128
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 732
telemt_desync_full_logged_total 183
telemt_desync_suppressed_total 549
telemt_desync_frames_bucket_total{bucket="1_2"} 259
telemt_desync_frames_bucket_total{bucket="3_10"} 234
telemt_desync_frames_bucket_total{bucket="gt_10"} 239
telemt_pool_swap_total 8
telemt_pool_force_close_total 319
telemt_pool_stale_pick_total 203
telemt_me_writer_removed_unexpected_total 9615
telemt_me_writer_restored_same_endpoint_total 7057
telemt_me_writer_removed_unexpected_minus_restored_total 2558
telemt_user_connections_total{user="hello"} 157133
telemt_user_connections_current{user="hello"} 258
telemt_user_octets_from_client{user="hello"} 9618460340 (8.96 GB)
telemt_user_octets_to_client{user="hello"} 52511375320 (48.91 GB)
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 37
```