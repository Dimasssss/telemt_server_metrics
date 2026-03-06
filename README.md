# Server Metrics 2026-03-06 23:48:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 20438.2 (5h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 283669
telemt_connections_bad_total 3004
telemt_handshake_timeouts_total 9282
telemt_upstream_connect_attempt_total 49732
telemt_upstream_connect_success_total 48616
telemt_upstream_connect_fail_total 979
telemt_upstream_connect_attempts_per_request{bucket="1"} 49595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17248
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31141
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 84
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 979
telemt_me_keepalive_timeout_total 1422
telemt_me_reconnect_attempts_total 24899
telemt_me_reconnect_success_total 23966
telemt_me_reader_eof_total 26859
telemt_me_idle_close_by_peer_total 26859
telemt_me_route_drop_no_conn_total 110837
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 166
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 992
telemt_desync_full_logged_total 265
telemt_desync_suppressed_total 727
telemt_desync_frames_bucket_total{bucket="1_2"} 271
telemt_desync_frames_bucket_total{bucket="3_10"} 447
telemt_desync_frames_bucket_total{bucket="gt_10"} 274
telemt_pool_swap_total 7
telemt_pool_force_close_total 410
telemt_pool_stale_pick_total 179
telemt_me_writer_removed_unexpected_total 26971
telemt_me_writer_restored_same_endpoint_total 23905
telemt_me_writer_restored_fallback_total 55
telemt_me_async_recovery_trigger_total 17428
telemt_me_writer_removed_unexpected_minus_restored_total 3011
telemt_user_connections_total{user="hello"} 256863
telemt_user_connections_current{user="hello"} 352
telemt_user_octets_from_client{user="hello"} 4044564300 (3.77 GB)
telemt_user_octets_to_client{user="hello"} 115472781964 (107.54 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 20438.3 (5h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118986
telemt_connections_bad_total 111
telemt_handshake_timeouts_total 12570
telemt_upstream_connect_attempt_total 82901
telemt_upstream_connect_success_total 82899
telemt_upstream_connect_attempts_per_request{bucket="1"} 82899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29420
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 919
telemt_me_reconnect_attempts_total 55063
telemt_me_reconnect_success_total 54847
telemt_me_reader_eof_total 52969
telemt_me_idle_close_by_peer_total 52964
telemt_me_route_drop_no_conn_total 40011
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 175
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 801
telemt_desync_full_logged_total 209
telemt_desync_suppressed_total 592
telemt_desync_frames_bucket_total{bucket="1_2"} 135
telemt_desync_frames_bucket_total{bucket="3_10"} 404
telemt_desync_frames_bucket_total{bucket="gt_10"} 262
telemt_pool_swap_total 12
telemt_pool_force_close_total 699
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 52994
telemt_me_writer_restored_same_endpoint_total 54845
telemt_me_async_recovery_trigger_total 17423
telemt_user_connections_total{user="hello"} 100355
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 1495267200 (1.39 GB)
telemt_user_octets_to_client{user="hello"} 36417540588 (33.92 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 20438.3 (5h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 219039
telemt_connections_bad_total 1110
telemt_handshake_timeouts_total 3523
telemt_upstream_connect_attempt_total 64497
telemt_upstream_connect_success_total 64334
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 64387
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25568
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 1669
telemt_me_reconnect_attempts_total 40343
telemt_me_reconnect_success_total 40293
telemt_me_reader_eof_total 41803
telemt_me_idle_close_by_peer_total 41799
telemt_me_route_drop_no_conn_total 82845
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 169
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1028
telemt_desync_full_logged_total 257
telemt_desync_suppressed_total 771
telemt_desync_frames_bucket_total{bucket="1_2"} 193
telemt_desync_frames_bucket_total{bucket="3_10"} 423
telemt_desync_frames_bucket_total{bucket="gt_10"} 412
telemt_pool_swap_total 11
telemt_pool_force_close_total 316
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 41965
telemt_me_writer_restored_same_endpoint_total 40286
telemt_me_async_recovery_trigger_total 52110
telemt_me_writer_removed_unexpected_minus_restored_total 1679
telemt_user_connections_total{user="hello"} 203730
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 16447765556 (15.32 GB)
telemt_user_octets_to_client{user="hello"} 59690918376 (55.59 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 20438.5 (5h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 219109
telemt_connections_bad_total 58338
telemt_handshake_timeouts_total 16174
telemt_upstream_connect_attempt_total 35390
telemt_upstream_connect_success_total 35308
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 35342
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14615
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20660
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 703
telemt_me_reconnect_attempts_total 11187
telemt_me_reconnect_success_total 11165
telemt_me_reader_eof_total 15139
telemt_me_idle_close_by_peer_total 15137
telemt_me_route_drop_no_conn_total 59224
telemt_me_single_endpoint_shadow_rotate_total 171
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 199
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 115
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_pool_swap_total 11
telemt_pool_force_close_total 393
telemt_pool_stale_pick_total 453
telemt_me_writer_removed_unexpected_total 15144
telemt_me_writer_restored_same_endpoint_total 11160
telemt_me_writer_removed_unexpected_minus_restored_total 3984
telemt_user_connections_total{user="hello"} 140810
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 1667818708 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 46626235596 (43.42 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 20437.1 (5h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 191306
telemt_connections_bad_total 494
telemt_handshake_timeouts_total 1914
telemt_upstream_connect_attempt_total 31905
telemt_upstream_connect_success_total 31760
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 31779
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12751
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18788
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 212
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 970
telemt_me_reconnect_attempts_total 9077
telemt_me_reconnect_success_total 9046
telemt_me_reader_eof_total 12193
telemt_me_idle_close_by_peer_total 12192
telemt_me_route_drop_no_conn_total 64381
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 165
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 758
telemt_desync_full_logged_total 194
telemt_desync_suppressed_total 564
telemt_desync_frames_bucket_total{bucket="1_2"} 265
telemt_desync_frames_bucket_total{bucket="3_10"} 246
telemt_desync_frames_bucket_total{bucket="gt_10"} 247
telemt_pool_swap_total 12
telemt_pool_force_close_total 379
telemt_pool_stale_pick_total 215
telemt_me_writer_removed_unexpected_total 12260
telemt_me_writer_restored_same_endpoint_total 9042
telemt_me_writer_removed_unexpected_minus_restored_total 3218
telemt_user_connections_total{user="hello"} 175366
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 10068059540 (9.38 GB)
telemt_user_octets_to_client{user="hello"} 60023242032 (55.90 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 29
```