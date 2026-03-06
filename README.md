# Server Metrics 2026-03-06 23:58:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 21052.9 (5h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 286756
telemt_connections_bad_total 3004
telemt_handshake_timeouts_total 9304
telemt_upstream_connect_attempt_total 52574
telemt_upstream_connect_success_total 51315
telemt_upstream_connect_fail_total 1122
telemt_upstream_connect_attempts_per_request{bucket="1"} 52437
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32960
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 86
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1122
telemt_me_keepalive_timeout_total 1449
telemt_me_reconnect_attempts_total 27072
telemt_me_reconnect_success_total 26001
telemt_me_reader_eof_total 28708
telemt_me_idle_close_by_peer_total 28708
telemt_me_route_drop_no_conn_total 111532
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 172
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 993
telemt_desync_full_logged_total 266
telemt_desync_suppressed_total 727
telemt_desync_frames_bucket_total{bucket="1_2"} 272
telemt_desync_frames_bucket_total{bucket="3_10"} 447
telemt_desync_frames_bucket_total{bucket="gt_10"} 274
telemt_pool_swap_total 8
telemt_pool_force_close_total 435
telemt_pool_stale_pick_total 181
telemt_me_writer_removed_unexpected_total 28820
telemt_me_writer_restored_same_endpoint_total 25932
telemt_me_writer_restored_fallback_total 63
telemt_me_async_recovery_trigger_total 19873
telemt_me_writer_removed_unexpected_minus_restored_total 2825
telemt_user_connections_total{user="hello"} 259852
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 4077033056 (3.80 GB)
telemt_user_octets_to_client{user="hello"} 116016450512 (108.05 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 21052.9 (5h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120751
telemt_connections_bad_total 111
telemt_handshake_timeouts_total 13078
telemt_upstream_connect_attempt_total 90802
telemt_upstream_connect_success_total 90800
telemt_upstream_connect_attempts_per_request{bucket="1"} 90800
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60295
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30474
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 970
telemt_me_reconnect_attempts_total 61906
telemt_me_reconnect_success_total 61669
telemt_me_reader_eof_total 58476
telemt_me_idle_close_by_peer_total 58471
telemt_me_route_drop_no_conn_total 40240
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 183
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 804
telemt_desync_full_logged_total 210
telemt_desync_suppressed_total 594
telemt_desync_frames_bucket_total{bucket="1_2"} 138
telemt_desync_frames_bucket_total{bucket="3_10"} 404
telemt_desync_frames_bucket_total{bucket="gt_10"} 262
telemt_pool_swap_total 13
telemt_pool_force_close_total 771
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 58501
telemt_me_writer_restored_same_endpoint_total 61667
telemt_me_async_recovery_trigger_total 19868
telemt_user_connections_total{user="hello"} 101581
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 1499349648 (1.40 GB)
telemt_user_octets_to_client{user="hello"} 36484684212 (33.98 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 21052.7 (5h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 221463
telemt_connections_bad_total 1127
telemt_handshake_timeouts_total 3531
telemt_upstream_connect_attempt_total 71324
telemt_upstream_connect_success_total 71159
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 71215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43757
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27236
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 1746
telemt_me_reconnect_attempts_total 46200
telemt_me_reconnect_success_total 46148
telemt_me_reader_eof_total 48024
telemt_me_idle_close_by_peer_total 48020
telemt_me_route_drop_no_conn_total 83821
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 177
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1029
telemt_desync_full_logged_total 258
telemt_desync_suppressed_total 771
telemt_desync_frames_bucket_total{bucket="1_2"} 193
telemt_desync_frames_bucket_total{bucket="3_10"} 424
telemt_desync_frames_bucket_total{bucket="gt_10"} 412
telemt_pool_swap_total 11
telemt_pool_force_close_total 316
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 48186
telemt_me_writer_restored_same_endpoint_total 46141
telemt_me_async_recovery_trigger_total 59433
telemt_me_writer_removed_unexpected_minus_restored_total 2045
telemt_user_connections_total{user="hello"} 206107
telemt_user_connections_current{user="hello"} 201
telemt_user_octets_from_client{user="hello"} 16976138420 (15.81 GB)
telemt_user_octets_to_client{user="hello"} 60052208044 (55.93 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 21053.1 (5h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 221345
telemt_connections_bad_total 58891
telemt_handshake_timeouts_total 16181
telemt_upstream_connect_attempt_total 36486
telemt_upstream_connect_success_total 36405
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 36439
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21365
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 727
telemt_me_reconnect_attempts_total 11483
telemt_me_reconnect_success_total 11461
telemt_me_reader_eof_total 15535
telemt_me_idle_close_by_peer_total 15533
telemt_me_route_drop_no_conn_total 60029
telemt_me_single_endpoint_shadow_rotate_total 179
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 202
telemt_desync_full_logged_total 85
telemt_desync_suppressed_total 117
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_pool_swap_total 12
telemt_pool_force_close_total 417
telemt_pool_stale_pick_total 460
telemt_me_writer_removed_unexpected_total 15540
telemt_me_writer_restored_same_endpoint_total 11456
telemt_me_writer_removed_unexpected_minus_restored_total 4084
telemt_user_connections_total{user="hello"} 142441
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 1672078020 (1.56 GB)
telemt_user_octets_to_client{user="hello"} 46794983484 (43.58 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 21051.5 (5h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 193754
telemt_connections_bad_total 501
telemt_handshake_timeouts_total 1974
telemt_upstream_connect_attempt_total 33302
telemt_upstream_connect_success_total 33155
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 33174
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13243
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19681
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 990
telemt_me_reconnect_attempts_total 9546
telemt_me_reconnect_success_total 9514
telemt_me_reader_eof_total 12854
telemt_me_idle_close_by_peer_total 12853
telemt_me_route_drop_no_conn_total 65309
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 173
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
telemt_me_writer_removed_unexpected_total 12921
telemt_me_writer_restored_same_endpoint_total 9510
telemt_me_writer_removed_unexpected_minus_restored_total 3411
telemt_user_connections_total{user="hello"} 177679
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 10077408668 (9.39 GB)
telemt_user_octets_to_client{user="hello"} 60516329400 (56.36 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 27
```