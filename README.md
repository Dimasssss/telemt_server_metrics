# Server Metrics 2026-03-06 01:18:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 10626.0 (2h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72727
telemt_connections_bad_total 15856
telemt_handshake_timeouts_total 670
telemt_upstream_connect_attempt_total 8864
telemt_upstream_connect_success_total 8796
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 8796
telemt_upstream_connect_attempts_per_request{bucket="2"} 31
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5207
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3575
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 101
telemt_me_reconnect_attempts_total 2257
telemt_me_reconnect_success_total 2244
telemt_me_reader_eof_total 2328
telemt_me_idle_close_by_peer_total 2328
telemt_me_route_drop_no_conn_total 16970
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 114
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 71
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 50
telemt_desync_frames_bucket_total{bucket="gt_10"} 21
telemt_pool_swap_total 1
telemt_pool_force_close_total 38
telemt_me_writer_removed_unexpected_total 2328
telemt_me_writer_restored_same_endpoint_total 2239
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 54734
telemt_user_connections_current{user="hello"} 383
telemt_user_octets_from_client{user="hello"} 622238388 (593.41 MB)
telemt_user_octets_to_client{user="hello"} 21358546124 (19.89 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 10621.5 (2h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23643
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 328
telemt_upstream_connect_attempt_total 8615
telemt_upstream_connect_success_total 8612
telemt_upstream_connect_attempts_per_request{bucket="1"} 8612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4900
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3709
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1628
telemt_me_reconnect_success_total 1621
telemt_me_reader_eof_total 1638
telemt_me_idle_close_by_peer_total 1638
telemt_me_route_drop_no_conn_total 6726
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 50
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_pool_swap_total 3
telemt_pool_force_close_total 44
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1639
telemt_me_writer_restored_same_endpoint_total 1617
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 22864
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 162097092 (154.59 MB)
telemt_user_octets_to_client{user="hello"} 5599169128 (5.21 GB)
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 10618.9 (2h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41749
telemt_connections_bad_total 309
telemt_handshake_timeouts_total 260
telemt_upstream_connect_attempt_total 11138
telemt_upstream_connect_success_total 11032
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 11032
telemt_upstream_connect_attempts_per_request{bucket="2"} 48
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6367
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4643
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 133
telemt_me_reconnect_attempts_total 3682
telemt_me_reconnect_success_total 3671
telemt_me_reader_eof_total 3856
telemt_me_idle_close_by_peer_total 3856
telemt_me_route_drop_no_conn_total 11098
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 89
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 1
telemt_pool_force_close_total 34
telemt_me_writer_removed_unexpected_total 3857
telemt_me_writer_restored_same_endpoint_total 3665
telemt_me_writer_removed_unexpected_minus_restored_total 192
telemt_user_connections_total{user="hello"} 39759
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 493830748 (470.95 MB)
telemt_user_octets_to_client{user="hello"} 17003719396 (15.84 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 10615.5 (2h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33292
telemt_connections_bad_total 215
telemt_handshake_timeouts_total 1940
telemt_upstream_connect_attempt_total 6932
telemt_upstream_connect_success_total 6909
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 6909
telemt_upstream_connect_attempts_per_request{bucket="2"} 11
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2835
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1258
telemt_me_reconnect_success_total 1250
telemt_me_reader_eof_total 1293
telemt_me_idle_close_by_peer_total 1293
telemt_me_route_drop_no_conn_total 13629
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 71
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 33
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 35
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 3
telemt_pool_force_close_total 52
telemt_me_writer_removed_unexpected_total 1293
telemt_me_writer_restored_same_endpoint_total 1245
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 29336
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 305040596 (290.91 MB)
telemt_user_octets_to_client{user="hello"} 17826447364 (16.60 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 10614.4 (2h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42362
telemt_connections_bad_total 85
telemt_handshake_timeouts_total 163
telemt_upstream_connect_attempt_total 5932
telemt_upstream_connect_success_total 5920
telemt_upstream_connect_attempts_per_request{bucket="1"} 5920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3870
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2013
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 72
telemt_me_reconnect_attempts_total 703
telemt_me_reconnect_success_total 701
telemt_me_reader_eof_total 714
telemt_me_idle_close_by_peer_total 714
telemt_me_route_drop_no_conn_total 13926
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 14
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 4
telemt_pool_force_close_total 57
telemt_me_writer_removed_unexpected_total 714
telemt_me_writer_restored_same_endpoint_total 696
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 41504
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 11037722952 (10.28 GB)
telemt_user_octets_to_client{user="hello"} 19027077664 (17.72 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 25
```