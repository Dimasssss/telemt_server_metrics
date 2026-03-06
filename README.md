# Server Metrics 2026-03-06 01:49:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 12468.8 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82813
telemt_connections_bad_total 15901
telemt_handshake_timeouts_total 760
telemt_upstream_connect_attempt_total 10397
telemt_upstream_connect_success_total 10290
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 10290
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6076
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4195
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 2811
telemt_me_reconnect_success_total 2796
telemt_me_reader_eof_total 2906
telemt_me_idle_close_by_peer_total 2906
telemt_me_route_drop_no_conn_total 19655
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 53
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 158
telemt_desync_full_logged_total 56
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_pool_swap_total 2
telemt_pool_force_close_total 89
telemt_me_writer_removed_unexpected_total 2906
telemt_me_writer_restored_same_endpoint_total 2790
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 64510
telemt_user_connections_current{user="hello"} 296
telemt_user_octets_from_client{user="hello"} 746716692 (712.12 MB)
telemt_user_octets_to_client{user="hello"} 23352571832 (21.75 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 12464.5 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27664
telemt_connections_bad_total 41
telemt_handshake_timeouts_total 363
telemt_upstream_connect_attempt_total 9654
telemt_upstream_connect_success_total 9652
telemt_upstream_connect_attempts_per_request{bucket="1"} 9652
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 129
telemt_me_reconnect_attempts_total 1679
telemt_me_reconnect_success_total 1671
telemt_me_reader_eof_total 1688
telemt_me_idle_close_by_peer_total 1688
telemt_me_route_drop_no_conn_total 7493
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 54
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
telemt_me_writer_removed_unexpected_total 1689
telemt_me_writer_restored_same_endpoint_total 1667
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 26810
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 176356332 (168.19 MB)
telemt_user_octets_to_client{user="hello"} 6078123544 (5.66 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 12461.8 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49915
telemt_connections_bad_total 489
telemt_handshake_timeouts_total 330
telemt_upstream_connect_attempt_total 12169
telemt_upstream_connect_success_total 12057
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 12057
telemt_upstream_connect_attempts_per_request{bucket="2"} 51
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7021
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5014
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 3845
telemt_me_reconnect_success_total 3834
telemt_me_reader_eof_total 4021
telemt_me_idle_close_by_peer_total 4021
telemt_me_route_drop_no_conn_total 12919
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 52
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 101
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 69
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_pool_swap_total 2
telemt_pool_force_close_total 60
telemt_me_writer_removed_unexpected_total 4022
telemt_me_writer_restored_same_endpoint_total 3827
telemt_me_writer_removed_unexpected_minus_restored_total 195
telemt_user_connections_total{user="hello"} 47135
telemt_user_connections_current{user="hello"} 253
telemt_user_octets_from_client{user="hello"} 539805376 (514.80 MB)
telemt_user_octets_to_client{user="hello"} 18396532568 (17.13 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 12458.5 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39354
telemt_connections_bad_total 218
telemt_handshake_timeouts_total 2674
telemt_upstream_connect_attempt_total 8971
telemt_upstream_connect_success_total 8946
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 8946
telemt_upstream_connect_attempts_per_request{bucket="2"} 12
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5167
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3779
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 2026
telemt_me_reconnect_success_total 2015
telemt_me_reader_eof_total 2109
telemt_me_idle_close_by_peer_total 2109
telemt_me_route_drop_no_conn_total 16295
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 52
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 119
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 69
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 53
telemt_pool_swap_total 4
telemt_pool_force_close_total 85
telemt_me_writer_removed_unexpected_total 2109
telemt_me_writer_restored_same_endpoint_total 2010
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 34387
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 322172180 (307.25 MB)
telemt_user_octets_to_client{user="hello"} 19426744000 (18.09 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 12457.3 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49714
telemt_connections_bad_total 100
telemt_handshake_timeouts_total 208
telemt_upstream_connect_attempt_total 7150
telemt_upstream_connect_success_total 7134
telemt_upstream_connect_attempts_per_request{bucket="1"} 7134
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2534
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 93
telemt_me_reconnect_attempts_total 833
telemt_me_reconnect_success_total 830
telemt_me_reader_eof_total 844
telemt_me_idle_close_by_peer_total 844
telemt_me_route_drop_no_conn_total 15823
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 53
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 30
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 5
telemt_pool_force_close_total 79
telemt_me_writer_removed_unexpected_total 844
telemt_me_writer_restored_same_endpoint_total 825
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 48727
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 11061172556 (10.30 GB)
telemt_user_octets_to_client{user="hello"} 21234952336 (19.78 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 30
```