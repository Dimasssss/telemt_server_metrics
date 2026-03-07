# Server Metrics 2026-03-07 01:16:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 25676.3 (7h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 313004
telemt_connections_bad_total 3692
telemt_handshake_timeouts_total 9444
telemt_upstream_connect_attempt_total 77363
telemt_upstream_connect_success_total 75219
telemt_upstream_connect_fail_total 2008
telemt_upstream_connect_attempts_per_request{bucket="1"} 77227
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46901
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2008
telemt_me_keepalive_timeout_total 1711
telemt_me_reconnect_attempts_total 45987
telemt_me_reconnect_success_total 44044
telemt_me_reader_eof_total 46206
telemt_me_idle_close_by_peer_total 46206
telemt_me_route_drop_no_conn_total 118670
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 210
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1008
telemt_desync_full_logged_total 274
telemt_desync_suppressed_total 734
telemt_desync_frames_bucket_total{bucket="1_2"} 279
telemt_desync_frames_bucket_total{bucket="3_10"} 454
telemt_desync_frames_bucket_total{bucket="gt_10"} 275
telemt_pool_swap_total 12
telemt_pool_force_close_total 570
telemt_pool_stale_pick_total 187
telemt_me_writer_removed_unexpected_total 46319
telemt_me_writer_restored_same_endpoint_total 43920
telemt_me_writer_restored_fallback_total 118
telemt_me_async_recovery_trigger_total 38263
telemt_me_writer_removed_unexpected_minus_restored_total 2281
telemt_user_connections_total{user="hello"} 284376
telemt_user_connections_current{user="hello"} 364
telemt_user_octets_from_client{user="hello"} 4319380532 (4.02 GB)
telemt_user_octets_to_client{user="hello"} 123492306556 (115.01 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 25676.2 (7h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134697
telemt_connections_bad_total 120
telemt_handshake_timeouts_total 16590
telemt_upstream_connect_attempt_total 154572
telemt_upstream_connect_success_total 154569
telemt_upstream_connect_attempts_per_request{bucket="1"} 154569
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 114874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39662
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 1281
telemt_me_reconnect_attempts_total 117839
telemt_me_reconnect_success_total 117536
telemt_me_reader_eof_total 107008
telemt_me_idle_close_by_peer_total 107003
telemt_me_route_drop_no_conn_total 42900
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 223
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 810
telemt_desync_full_logged_total 215
telemt_desync_suppressed_total 595
telemt_desync_frames_bucket_total{bucket="1_2"} 141
telemt_desync_frames_bucket_total{bucket="3_10"} 407
telemt_desync_frames_bucket_total{bucket="gt_10"} 262
telemt_pool_swap_total 18
telemt_pool_force_close_total 1171
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 107038
telemt_me_writer_restored_same_endpoint_total 117534
telemt_me_async_recovery_trigger_total 38255
telemt_user_connections_total{user="hello"} 111382
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 1572245612 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 38343983776 (35.71 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 25676.1 (7h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 241908
telemt_connections_bad_total 1260
telemt_handshake_timeouts_total 3596
telemt_upstream_connect_attempt_total 113921
telemt_upstream_connect_success_total 113739
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 113807
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38818
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 2261
telemt_me_reconnect_attempts_total 82099
telemt_me_reconnect_success_total 82027
telemt_me_reader_eof_total 84087
telemt_me_idle_close_by_peer_total 84082
telemt_me_route_drop_no_conn_total 90777
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 213
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1046
telemt_desync_full_logged_total 268
telemt_desync_suppressed_total 778
telemt_desync_frames_bucket_total{bucket="1_2"} 198
telemt_desync_frames_bucket_total{bucket="3_10"} 429
telemt_desync_frames_bucket_total{bucket="gt_10"} 419
telemt_pool_swap_total 14
telemt_pool_force_close_total 372
telemt_pool_stale_pick_total 126
telemt_me_writer_removed_unexpected_total 84256
telemt_me_writer_restored_same_endpoint_total 82020
telemt_me_async_recovery_trigger_total 114557
telemt_me_writer_removed_unexpected_minus_restored_total 2236
telemt_user_connections_total{user="hello"} 226211
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 21168599076 (19.71 GB)
telemt_user_octets_to_client{user="hello"} 64557529080 (60.12 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 25676.5 (7h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 248179
telemt_connections_bad_total 72544
telemt_handshake_timeouts_total 16941
telemt_upstream_connect_attempt_total 46801
telemt_upstream_connect_success_total 46714
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 46754
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27960
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 913
telemt_me_reconnect_attempts_total 15263
telemt_me_reconnect_success_total 15234
telemt_me_reader_eof_total 20888
telemt_me_idle_close_by_peer_total 20886
telemt_me_route_drop_no_conn_total 66050
telemt_me_single_endpoint_shadow_rotate_total 216
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 221
telemt_desync_full_logged_total 98
telemt_desync_suppressed_total 123
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 80
telemt_desync_frames_bucket_total{bucket="gt_10"} 64
telemt_pool_swap_total 13
telemt_pool_force_close_total 453
telemt_pool_stale_pick_total 474
telemt_me_writer_removed_unexpected_total 20893
telemt_me_writer_restored_same_endpoint_total 15229
telemt_me_writer_removed_unexpected_minus_restored_total 5664
telemt_user_connections_total{user="hello"} 154636
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 1743728600 (1.62 GB)
telemt_user_octets_to_client{user="hello"} 50065681832 (46.63 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 25675.0 (7h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 212204
telemt_connections_bad_total 511
telemt_handshake_timeouts_total 2531
telemt_upstream_connect_attempt_total 43000
telemt_upstream_connect_success_total 42842
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 42862
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16761
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25807
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 265
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 1197
telemt_me_reconnect_attempts_total 12809
telemt_me_reconnect_success_total 12774
telemt_me_reader_eof_total 17519
telemt_me_idle_close_by_peer_total 17517
telemt_me_route_drop_no_conn_total 70916
telemt_me_route_drop_channel_closed_total 4
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 212
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 799
telemt_desync_full_logged_total 206
telemt_desync_suppressed_total 593
telemt_desync_frames_bucket_total{bucket="1_2"} 273
telemt_desync_frames_bucket_total{bucket="3_10"} 263
telemt_desync_frames_bucket_total{bucket="gt_10"} 263
telemt_pool_swap_total 15
telemt_pool_force_close_total 453
telemt_pool_stale_pick_total 215
telemt_me_writer_removed_unexpected_total 17586
telemt_me_writer_restored_same_endpoint_total 12766
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 4816
telemt_user_connections_total{user="hello"} 194798
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 10197592268 (9.50 GB)
telemt_user_octets_to_client{user="hello"} 68149995788 (63.47 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 19
```