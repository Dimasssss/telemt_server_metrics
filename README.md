# Server Metrics 2026-03-04 01:12:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 14513.5 (4h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98405
telemt_connections_bad_total 893
telemt_handshake_timeouts_total 520
telemt_upstream_connect_attempt_total 11151
telemt_upstream_connect_success_total 11100
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 11100
telemt_upstream_connect_attempts_per_request{bucket="2"} 21
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6192
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4888
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 2821
telemt_me_reconnect_success_total 2823
telemt_me_reader_eof_total 2885
telemt_me_idle_close_by_peer_total 2885
telemt_me_route_drop_no_conn_total 36907
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 145
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 96
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 2
telemt_pool_force_close_total 78
telemt_me_writer_removed_unexpected_total 2885
telemt_me_writer_restored_same_endpoint_total 2803
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 94689
telemt_user_connections_current{user="hello"} 309
telemt_user_octets_from_client{user="hello"} 720203636 (686.84 MB)
telemt_user_octets_to_client{user="hello"} 29100933020 (27.10 GB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 14510.1 (4h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46089
telemt_connections_bad_total 104
telemt_handshake_timeouts_total 11265
telemt_upstream_connect_attempt_total 29325
telemt_upstream_connect_success_total 28967
telemt_upstream_connect_fail_total 163
telemt_upstream_connect_attempts_per_request{bucket="1"} 28961
telemt_upstream_connect_attempts_per_request{bucket="2"} 169
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9266
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 163
telemt_me_keepalive_timeout_total 650
telemt_me_reconnect_attempts_total 16679
telemt_me_reconnect_success_total 16670
telemt_me_reader_eof_total 17062
telemt_me_idle_close_by_peer_total 17061
telemt_me_route_drop_no_conn_total 16550
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 65
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 79
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 31
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_me_writer_removed_unexpected_total 17123
telemt_me_writer_restored_same_endpoint_total 16650
telemt_me_writer_removed_unexpected_minus_restored_total 473
telemt_user_connections_total{user="hello"} 34174
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 241250868 (230.07 MB)
telemt_user_octets_to_client{user="hello"} 20211660280 (18.82 GB)
telemt_user_unique_ips_current{user="hello"} 22
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 14508.9 (4h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107264
telemt_connections_bad_total 36349
telemt_handshake_timeouts_total 1971
telemt_upstream_connect_attempt_total 16390
telemt_upstream_connect_success_total 16301
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 16301
telemt_upstream_connect_attempts_per_request{bucket="2"} 40
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9475
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6768
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 206
telemt_me_reconnect_attempts_total 5696
telemt_me_reconnect_success_total 5691
telemt_me_reader_eof_total 5923
telemt_me_idle_close_by_peer_total 5921
telemt_me_route_drop_no_conn_total 20955
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 62
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 225
telemt_desync_full_logged_total 74
telemt_desync_suppressed_total 151
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 84
telemt_desync_frames_bucket_total{bucket="gt_10"} 95
telemt_pool_swap_total 2
telemt_pool_force_close_total 61
telemt_me_writer_removed_unexpected_total 5924
telemt_me_writer_restored_same_endpoint_total 5670
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 67620
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 411851768 (392.77 MB)
telemt_user_octets_to_client{user="hello"} 17355770600 (16.16 GB)
telemt_user_unique_ips_current{user="hello"} 27
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 14508.0 (4h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47726
telemt_connections_bad_total 168
telemt_handshake_timeouts_total 530
telemt_upstream_connect_attempt_total 9232
telemt_upstream_connect_success_total 9193
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 9193
telemt_upstream_connect_attempts_per_request{bucket="2"} 18
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3541
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 1317
telemt_me_reconnect_success_total 1327
telemt_me_reader_eof_total 1328
telemt_me_idle_close_by_peer_total 1328
telemt_me_route_drop_no_conn_total 16473
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 62
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 15
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_pool_swap_total 4
telemt_pool_force_close_total 101
telemt_me_writer_removed_unexpected_total 1328
telemt_me_writer_restored_same_endpoint_total 1307
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 46218
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 406098384 (387.29 MB)
telemt_user_octets_to_client{user="hello"} 12327936448 (11.48 GB)
telemt_user_unique_ips_current{user="hello"} 28
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 14506.5 (4h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115776
telemt_connections_bad_total 52
telemt_handshake_timeouts_total 50238
telemt_upstream_connect_attempt_total 21755
telemt_upstream_connect_success_total 21626
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 21626
telemt_upstream_connect_attempts_per_request{bucket="2"} 60
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12278
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9306
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 291
telemt_me_reconnect_attempts_total 11239
telemt_me_reconnect_success_total 11240
telemt_me_reader_eof_total 11942
telemt_me_idle_close_by_peer_total 11941
telemt_me_route_drop_no_conn_total 37349
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 64
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 84
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 66
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 29
telemt_pool_swap_total 1
telemt_pool_force_close_total 30
telemt_me_writer_removed_unexpected_total 11948
telemt_me_writer_restored_same_endpoint_total 11216
telemt_me_writer_removed_unexpected_minus_restored_total 732
telemt_user_connections_total{user="hello"} 63317
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 308388180 (294.10 MB)
telemt_user_octets_to_client{user="hello"} 15369085936 (14.31 GB)
telemt_user_unique_ips_current{user="hello"} 15
```