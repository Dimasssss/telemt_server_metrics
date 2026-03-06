# Server Metrics 2026-03-06 01:33:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 11547.4 (3h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77646
telemt_connections_bad_total 15876
telemt_handshake_timeouts_total 723
telemt_upstream_connect_attempt_total 9934
telemt_upstream_connect_success_total 9845
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 9845
telemt_upstream_connect_attempts_per_request{bucket="2"} 41
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5816
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4011
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 117
telemt_me_reconnect_attempts_total 2750
telemt_me_reconnect_success_total 2735
telemt_me_reader_eof_total 2845
telemt_me_idle_close_by_peer_total 2845
telemt_me_route_drop_no_conn_total 18514
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 50
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 141
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 92
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 61
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_pool_swap_total 2
telemt_pool_force_close_total 89
telemt_me_writer_removed_unexpected_total 2845
telemt_me_writer_restored_same_endpoint_total 2730
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 59483
telemt_user_connections_current{user="hello"} 363
telemt_user_octets_from_client{user="hello"} 665963056 (635.11 MB)
telemt_user_octets_to_client{user="hello"} 22472235036 (20.93 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 11542.9 (3h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25840
telemt_connections_bad_total 39
telemt_handshake_timeouts_total 344
telemt_upstream_connect_attempt_total 9090
telemt_upstream_connect_success_total 9088
telemt_upstream_connect_attempts_per_request{bucket="1"} 9088
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3925
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 1661
telemt_me_reconnect_success_total 1653
telemt_me_reader_eof_total 1670
telemt_me_idle_close_by_peer_total 1670
telemt_me_route_drop_no_conn_total 7157
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 50
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 50
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_pool_swap_total 4
telemt_pool_force_close_total 51
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1671
telemt_me_writer_restored_same_endpoint_total 1649
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 25027
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 166713436 (158.99 MB)
telemt_user_octets_to_client{user="hello"} 5694410136 (5.30 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 11540.2 (3h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45875
telemt_connections_bad_total 322
telemt_handshake_timeouts_total 293
telemt_upstream_connect_attempt_total 11757
telemt_upstream_connect_success_total 11647
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 11647
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4872
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 141
telemt_me_reconnect_attempts_total 3814
telemt_me_reconnect_success_total 3803
telemt_me_reader_eof_total 3990
telemt_me_idle_close_by_peer_total 3990
telemt_me_route_drop_no_conn_total 11859
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 48
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 89
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 2
telemt_pool_force_close_total 60
telemt_me_writer_removed_unexpected_total 3991
telemt_me_writer_restored_same_endpoint_total 3796
telemt_me_writer_removed_unexpected_minus_restored_total 195
telemt_user_connections_total{user="hello"} 43383
telemt_user_connections_current{user="hello"} 222
telemt_user_octets_from_client{user="hello"} 525705736 (501.35 MB)
telemt_user_octets_to_client{user="hello"} 17503516420 (16.30 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 11536.9 (3h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36511
telemt_connections_bad_total 217
telemt_handshake_timeouts_total 2607
telemt_upstream_connect_attempt_total 8380
telemt_upstream_connect_success_total 8354
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 8354
telemt_upstream_connect_attempts_per_request{bucket="2"} 12
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4844
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3510
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 91
telemt_me_reconnect_attempts_total 1861
telemt_me_reconnect_success_total 1851
telemt_me_reader_eof_total 1931
telemt_me_idle_close_by_peer_total 1931
telemt_me_route_drop_no_conn_total 15787
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 49
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 111
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 65
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_pool_swap_total 3
telemt_pool_force_close_total 52
telemt_me_writer_removed_unexpected_total 1931
telemt_me_writer_restored_same_endpoint_total 1846
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 31952
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 314859920 (300.27 MB)
telemt_user_octets_to_client{user="hello"} 18992532884 (17.69 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 11535.9 (3h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46098
telemt_connections_bad_total 91
telemt_handshake_timeouts_total 200
telemt_upstream_connect_attempt_total 6700
telemt_upstream_connect_success_total 6685
telemt_upstream_connect_attempts_per_request{bucket="1"} 6685
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4285
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2359
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 88
telemt_me_reconnect_attempts_total 801
telemt_me_reconnect_success_total 798
telemt_me_reader_eof_total 811
telemt_me_idle_close_by_peer_total 811
telemt_me_route_drop_no_conn_total 14920
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 50
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 16
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 8
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 4
telemt_pool_force_close_total 57
telemt_me_writer_removed_unexpected_total 811
telemt_me_writer_restored_same_endpoint_total 793
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 45165
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 11049884148 (10.29 GB)
telemt_user_octets_to_client{user="hello"} 20411480560 (19.01 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 27
```