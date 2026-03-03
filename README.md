# Server Metrics 2026-03-03 22:38:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 5299.6 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48442
telemt_connections_bad_total 639
telemt_handshake_timeouts_total 104
telemt_upstream_connect_attempt_total 2322
telemt_upstream_connect_success_total 2306
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 2306
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1329
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 970
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 28
telemt_me_reconnect_attempts_total 204
telemt_me_reconnect_success_total 216
telemt_me_reader_eof_total 199
telemt_me_idle_close_by_peer_total 199
telemt_me_route_drop_no_conn_total 18528
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 83
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 50
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_pool_swap_total 1
telemt_pool_force_close_total 38
telemt_me_writer_removed_unexpected_total 199
telemt_me_writer_restored_same_endpoint_total 196
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 46655
telemt_user_connections_current{user="hello"} 372
telemt_user_octets_from_client{user="hello"} 450089804 (429.24 MB)
telemt_user_octets_to_client{user="hello"} 17207778112 (16.03 GB)
telemt_user_unique_ips_current{user="hello"} 48
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 5296.2 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20755
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 3974
telemt_upstream_connect_attempt_total 5318
telemt_upstream_connect_success_total 5164
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 5164
telemt_upstream_connect_attempts_per_request{bucket="2"} 74
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3299
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1863
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 54
telemt_me_reconnect_attempts_total 1796
telemt_me_reconnect_success_total 1809
telemt_me_reader_eof_total 1823
telemt_me_idle_close_by_peer_total 1822
telemt_me_route_drop_no_conn_total 7903
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 52
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 18
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_me_writer_removed_unexpected_total 1823
telemt_me_writer_restored_same_endpoint_total 1789
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 16474
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 94491168 (90.11 MB)
telemt_user_octets_to_client{user="hello"} 4836452880 (4.50 GB)
telemt_user_unique_ips_current{user="hello"} 20
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 5295.0 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52218
telemt_connections_bad_total 14510
telemt_handshake_timeouts_total 1521
telemt_upstream_connect_attempt_total 4363
telemt_upstream_connect_success_total 4330
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 4330
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2491
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1824
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 925
telemt_me_reconnect_success_total 940
telemt_me_reader_eof_total 948
telemt_me_idle_close_by_peer_total 948
telemt_me_route_drop_no_conn_total 10835
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 120
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 77
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 948
telemt_me_writer_restored_same_endpoint_total 919
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 35123
telemt_user_connections_current{user="hello"} 176
telemt_user_octets_from_client{user="hello"} 269863624 (257.36 MB)
telemt_user_octets_to_client{user="hello"} 12014146684 (11.19 GB)
telemt_user_unique_ips_current{user="hello"} 29
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 5294.0 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23453
telemt_connections_bad_total 54
telemt_handshake_timeouts_total 352
telemt_upstream_connect_attempt_total 2814
telemt_upstream_connect_success_total 2795
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2795
telemt_upstream_connect_attempts_per_request{bucket="2"} 9
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1124
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 266
telemt_me_reconnect_success_total 282
telemt_me_reader_eof_total 265
telemt_me_idle_close_by_peer_total 265
telemt_me_route_drop_no_conn_total 9200
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 8
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 1
telemt_pool_force_close_total 41
telemt_me_writer_removed_unexpected_total 265
telemt_me_writer_restored_same_endpoint_total 263
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 22711
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 182955208 (174.48 MB)
telemt_user_octets_to_client{user="hello"} 7651447164 (7.13 GB)
telemt_user_unique_ips_current{user="hello"} 22
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 5293.0 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49851
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 15981
telemt_upstream_connect_attempt_total 2671
telemt_upstream_connect_success_total 2627
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 2627
telemt_upstream_connect_attempts_per_request{bucket="2"} 20
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1715
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 907
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 472
telemt_me_reconnect_success_total 489
telemt_me_reader_eof_total 477
telemt_me_idle_close_by_peer_total 477
telemt_me_route_drop_no_conn_total 27555
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 11
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 1
telemt_pool_force_close_total 30
telemt_me_writer_removed_unexpected_total 477
telemt_me_writer_restored_same_endpoint_total 465
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 32893
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 178936864 (170.65 MB)
telemt_user_octets_to_client{user="hello"} 8049861460 (7.50 GB)
telemt_user_unique_ips_current{user="hello"} 30
```