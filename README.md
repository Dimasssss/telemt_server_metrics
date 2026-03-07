# Server Metrics 2026-03-07 01:10:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 25369.3 (7h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 311320
telemt_connections_bad_total 3691
telemt_handshake_timeouts_total 9432
telemt_upstream_connect_attempt_total 75437
telemt_upstream_connect_success_total 73315
telemt_upstream_connect_fail_total 1985
telemt_upstream_connect_attempts_per_request{bucket="1"} 75300
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27065
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46010
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 90
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1985
telemt_me_keepalive_timeout_total 1696
telemt_me_reconnect_attempts_total 44378
telemt_me_reconnect_success_total 42458
telemt_me_reader_eof_total 44914
telemt_me_idle_close_by_peer_total 44914
telemt_me_route_drop_no_conn_total 118241
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
telemt_pool_force_close_total 540
telemt_pool_stale_pick_total 187
telemt_me_writer_removed_unexpected_total 45027
telemt_me_writer_restored_same_endpoint_total 42336
telemt_me_writer_restored_fallback_total 116
telemt_me_async_recovery_trigger_total 37042
telemt_me_writer_removed_unexpected_minus_restored_total 2575
telemt_user_connections_total{user="hello"} 282727
telemt_user_connections_current{user="hello"} 371
telemt_user_octets_from_client{user="hello"} 4301021856 (4.01 GB)
telemt_user_octets_to_client{user="hello"} 123096592976 (114.64 GB)
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 25369.1 (7h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133900
telemt_connections_bad_total 119
telemt_handshake_timeouts_total 16409
telemt_upstream_connect_attempt_total 150602
telemt_upstream_connect_success_total 150599
telemt_upstream_connect_attempts_per_request{bucket="1"} 150599
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111606
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38960
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 1260
telemt_me_reconnect_attempts_total 114357
telemt_me_reconnect_success_total 114056
telemt_me_reader_eof_total 104253
telemt_me_idle_close_by_peer_total 104248
telemt_me_route_drop_no_conn_total 42788
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
telemt_pool_force_close_total 1102
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 104283
telemt_me_writer_restored_same_endpoint_total 114054
telemt_me_async_recovery_trigger_total 37034
telemt_user_connections_total{user="hello"} 110783
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 1570067100 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 38083512148 (35.47 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 25369.0 (7h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 240890
telemt_connections_bad_total 1260
telemt_handshake_timeouts_total 3596
telemt_upstream_connect_attempt_total 111645
telemt_upstream_connect_success_total 111463
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 111530
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73191
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38070
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 198
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 2220
telemt_me_reconnect_attempts_total 80272
telemt_me_reconnect_success_total 80203
telemt_me_reader_eof_total 82013
telemt_me_idle_close_by_peer_total 82008
telemt_me_route_drop_no_conn_total 90517
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 212
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
telemt_me_writer_removed_unexpected_total 82182
telemt_me_writer_restored_same_endpoint_total 80196
telemt_me_async_recovery_trigger_total 110894
telemt_me_writer_removed_unexpected_minus_restored_total 1986
telemt_user_connections_total{user="hello"} 225196
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 20874938416 (19.44 GB)
telemt_user_octets_to_client{user="hello"} 64311920308 (59.90 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 25369.3 (7h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 246436
telemt_connections_bad_total 71566
telemt_handshake_timeouts_total 16941
telemt_upstream_connect_attempt_total 45919
telemt_upstream_connect_success_total 45831
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 45871
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18423
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27374
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 890
telemt_me_reconnect_attempts_total 14866
telemt_me_reconnect_success_total 14838
telemt_me_reader_eof_total 20301
telemt_me_idle_close_by_peer_total 20299
telemt_me_route_drop_no_conn_total 65828
telemt_me_single_endpoint_shadow_rotate_total 216
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 219
telemt_desync_full_logged_total 97
telemt_desync_suppressed_total 122
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 79
telemt_desync_frames_bucket_total{bucket="gt_10"} 63
telemt_pool_swap_total 13
telemt_pool_force_close_total 453
telemt_pool_stale_pick_total 474
telemt_me_writer_removed_unexpected_total 20306
telemt_me_writer_restored_same_endpoint_total 14833
telemt_me_writer_removed_unexpected_minus_restored_total 5473
telemt_user_connections_total{user="hello"} 153885
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 1740245796 (1.62 GB)
telemt_user_octets_to_client{user="hello"} 49974228104 (46.54 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 25367.9 (7h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211189
telemt_connections_bad_total 510
telemt_handshake_timeouts_total 2502
telemt_upstream_connect_attempt_total 42682
telemt_upstream_connect_success_total 42525
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 42545
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16635
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25618
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 263
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 1184
telemt_me_reconnect_attempts_total 12809
telemt_me_reconnect_success_total 12774
telemt_me_reader_eof_total 17519
telemt_me_idle_close_by_peer_total 17517
telemt_me_route_drop_no_conn_total 70723
telemt_me_route_drop_channel_closed_total 4
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 210
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 799
telemt_desync_full_logged_total 206
telemt_desync_suppressed_total 593
telemt_desync_frames_bucket_total{bucket="1_2"} 273
telemt_desync_frames_bucket_total{bucket="3_10"} 263
telemt_desync_frames_bucket_total{bucket="gt_10"} 263
telemt_pool_swap_total 15
telemt_pool_force_close_total 428
telemt_pool_stale_pick_total 215
telemt_me_writer_removed_unexpected_total 17586
telemt_me_writer_restored_same_endpoint_total 12766
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 4816
telemt_user_connections_total{user="hello"} 193865
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 10195705632 (9.50 GB)
telemt_user_octets_to_client{user="hello"} 68104736588 (63.43 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 21
```