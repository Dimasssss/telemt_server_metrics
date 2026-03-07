# Server Metrics 2026-03-07 00:34:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 23205.9 (6h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 298799
telemt_connections_bad_total 3032
telemt_handshake_timeouts_total 9385
telemt_upstream_connect_attempt_total 63880
telemt_upstream_connect_success_total 62196
telemt_upstream_connect_fail_total 1548
telemt_upstream_connect_attempts_per_request{bucket="1"} 63744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39621
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 89
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1548
telemt_me_keepalive_timeout_total 1587
telemt_me_reconnect_attempts_total 35699
telemt_me_reconnect_success_total 34206
telemt_me_reader_eof_total 37129
telemt_me_idle_close_by_peer_total 37129
telemt_me_route_drop_no_conn_total 115236
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 188
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 998
telemt_desync_full_logged_total 268
telemt_desync_suppressed_total 730
telemt_desync_frames_bucket_total{bucket="1_2"} 275
telemt_desync_frames_bucket_total{bucket="3_10"} 448
telemt_desync_frames_bucket_total{bucket="gt_10"} 275
telemt_pool_swap_total 9
telemt_pool_force_close_total 474
telemt_pool_stale_pick_total 186
telemt_me_writer_removed_unexpected_total 37242
telemt_me_writer_restored_same_endpoint_total 34110
telemt_me_writer_restored_fallback_total 90
telemt_me_async_recovery_trigger_total 28437
telemt_me_writer_removed_unexpected_minus_restored_total 3042
telemt_user_connections_total{user="hello"} 271533
telemt_user_connections_current{user="hello"} 347
telemt_user_octets_from_client{user="hello"} 4202343192 (3.91 GB)
telemt_user_octets_to_client{user="hello"} 119774268436 (111.55 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 23205.9 (6h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127242
telemt_connections_bad_total 114
telemt_handshake_timeouts_total 14819
telemt_upstream_connect_attempt_total 122236
telemt_upstream_connect_success_total 122233
telemt_upstream_connect_attempts_per_request{bucket="1"} 122233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 87391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34811
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 1112
telemt_me_reconnect_attempts_total 89726
telemt_me_reconnect_success_total 89462
telemt_me_reader_eof_total 82959
telemt_me_idle_close_by_peer_total 82954
telemt_me_route_drop_no_conn_total 41509
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 199
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 808
telemt_desync_full_logged_total 213
telemt_desync_suppressed_total 595
telemt_desync_frames_bucket_total{bucket="1_2"} 140
telemt_desync_frames_bucket_total{bucket="3_10"} 406
telemt_desync_frames_bucket_total{bucket="gt_10"} 262
telemt_pool_swap_total 15
telemt_pool_force_close_total 959
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 82988
telemt_me_writer_restored_same_endpoint_total 89460
telemt_me_async_recovery_trigger_total 28430
telemt_user_connections_total{user="hello"} 106129
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 1545299420 (1.44 GB)
telemt_user_octets_to_client{user="hello"} 37289141252 (34.73 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 23205.7 (6h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 231072
telemt_connections_bad_total 1228
telemt_handshake_timeouts_total 3570
telemt_upstream_connect_attempt_total 95194
telemt_upstream_connect_success_total 95024
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 95083
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62005
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32843
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 2015
telemt_me_reconnect_attempts_total 66903
telemt_me_reconnect_success_total 66843
telemt_me_reader_eof_total 68938
telemt_me_idle_close_by_peer_total 68933
telemt_me_route_drop_no_conn_total 87531
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 191
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1038
telemt_desync_full_logged_total 264
telemt_desync_suppressed_total 774
telemt_desync_frames_bucket_total{bucket="1_2"} 195
telemt_desync_frames_bucket_total{bucket="3_10"} 426
telemt_desync_frames_bucket_total{bucket="gt_10"} 417
telemt_pool_swap_total 12
telemt_pool_force_close_total 350
telemt_pool_stale_pick_total 124
telemt_me_writer_removed_unexpected_total 69106
telemt_me_writer_restored_same_endpoint_total 66836
telemt_me_async_recovery_trigger_total 85091
telemt_me_writer_removed_unexpected_minus_restored_total 2270
telemt_user_connections_total{user="hello"} 215513
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 19000483788 (17.70 GB)
telemt_user_octets_to_client{user="hello"} 61879238260 (57.63 GB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 23206.2 (6h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 233078
telemt_connections_bad_total 64653
telemt_handshake_timeouts_total 16648
telemt_upstream_connect_attempt_total 41398
telemt_upstream_connect_success_total 41315
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 41351
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24567
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 813
telemt_me_reconnect_attempts_total 13291
telemt_me_reconnect_success_total 13265
telemt_me_reader_eof_total 18074
telemt_me_idle_close_by_peer_total 18072
telemt_me_route_drop_no_conn_total 62934
telemt_me_single_endpoint_shadow_rotate_total 195
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 207
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 118
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 77
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 12
telemt_pool_force_close_total 417
telemt_pool_stale_pick_total 467
telemt_me_writer_removed_unexpected_total 18079
telemt_me_writer_restored_same_endpoint_total 13260
telemt_me_writer_removed_unexpected_minus_restored_total 4819
telemt_user_connections_total{user="hello"} 147840
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 1715915172 (1.60 GB)
telemt_user_octets_to_client{user="hello"} 48392279304 (45.07 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 23204.7 (6h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202109
telemt_connections_bad_total 504
telemt_handshake_timeouts_total 2265
telemt_upstream_connect_attempt_total 37096
telemt_upstream_connect_success_total 36947
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 36966
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14566
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22143
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 229
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 1076
telemt_me_reconnect_attempts_total 10521
telemt_me_reconnect_success_total 10488
telemt_me_reader_eof_total 14238
telemt_me_idle_close_by_peer_total 14236
telemt_me_route_drop_no_conn_total 67612
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 188
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 770
telemt_desync_full_logged_total 199
telemt_desync_suppressed_total 571
telemt_desync_frames_bucket_total{bucket="1_2"} 267
telemt_desync_frames_bucket_total{bucket="3_10"} 250
telemt_desync_frames_bucket_total{bucket="gt_10"} 253
telemt_pool_swap_total 14
telemt_pool_force_close_total 428
telemt_pool_stale_pick_total 215
telemt_me_writer_removed_unexpected_total 14305
telemt_me_writer_restored_same_endpoint_total 10484
telemt_me_writer_removed_unexpected_minus_restored_total 3821
telemt_user_connections_total{user="hello"} 185553
telemt_user_connections_current{user="hello"} 226
telemt_user_octets_from_client{user="hello"} 10124476052 (9.43 GB)
telemt_user_octets_to_client{user="hello"} 64976917412 (60.51 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 25
```