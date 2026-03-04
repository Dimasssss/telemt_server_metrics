# Server Metrics 2026-03-04 03:25:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 22497.0 (6h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143219
telemt_connections_bad_total 1533
telemt_handshake_timeouts_total 2379
telemt_upstream_connect_attempt_total 17373
telemt_upstream_connect_success_total 17300
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 17300
telemt_upstream_connect_attempts_per_request{bucket="2"} 32
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7547
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 181
telemt_me_reconnect_attempts_total 4253
telemt_me_reconnect_success_total 4242
telemt_me_reader_eof_total 4343
telemt_me_idle_close_by_peer_total 4343
telemt_me_route_drop_no_conn_total 49783
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 91
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 272
telemt_desync_full_logged_total 97
telemt_desync_suppressed_total 175
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 108
telemt_pool_swap_total 4
telemt_pool_force_close_total 139
telemt_me_writer_removed_unexpected_total 4343
telemt_me_writer_restored_same_endpoint_total 4222
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 136089
telemt_user_connections_current{user="hello"} 410
telemt_user_octets_from_client{user="hello"} 1276560852 (1.19 GB)
telemt_user_octets_to_client{user="hello"} 40713269964 (37.92 GB)
telemt_user_unique_ips_current{user="hello"} 60
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 22493.7 (6h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67403
telemt_connections_bad_total 280
telemt_handshake_timeouts_total 17232
telemt_upstream_connect_attempt_total 56724
telemt_upstream_connect_success_total 56162
telemt_upstream_connect_fail_total 265
telemt_upstream_connect_attempts_per_request{bucket="1"} 56156
telemt_upstream_connect_attempts_per_request{bucket="2"} 271
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17779
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 265
telemt_me_keepalive_timeout_total 904
telemt_me_reconnect_attempts_total 35727
telemt_me_reconnect_success_total 35704
telemt_me_reader_eof_total 36620
telemt_me_idle_close_by_peer_total 36619
telemt_me_route_drop_no_conn_total 22105
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 99
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 144
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 84
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 73
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_me_writer_removed_unexpected_total 36681
telemt_me_writer_restored_same_endpoint_total 35684
telemt_me_writer_removed_unexpected_minus_restored_total 997
telemt_user_connections_total{user="hello"} 49114
telemt_user_connections_current{user="hello"} 212
telemt_user_octets_from_client{user="hello"} 406842856 (388.00 MB)
telemt_user_octets_to_client{user="hello"} 25279724188 (23.54 GB)
telemt_user_unique_ips_current{user="hello"} 21
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 22492.4 (6h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156872
telemt_connections_bad_total 57235
telemt_handshake_timeouts_total 3571
telemt_upstream_connect_attempt_total 29967
telemt_upstream_connect_success_total 29759
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 29759
telemt_upstream_connect_attempts_per_request{bucket="2"} 96
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12264
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 376
telemt_me_reconnect_attempts_total 12015
telemt_me_reconnect_success_total 11990
telemt_me_reader_eof_total 12605
telemt_me_idle_close_by_peer_total 12602
telemt_me_route_drop_no_conn_total 30386
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 95
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 295
telemt_desync_full_logged_total 102
telemt_desync_suppressed_total 193
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 2
telemt_pool_force_close_total 63
telemt_me_writer_removed_unexpected_total 12610
telemt_me_writer_restored_same_endpoint_total 11969
telemt_me_writer_removed_unexpected_minus_restored_total 641
telemt_user_connections_total{user="hello"} 92589
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 578404520 (551.61 MB)
telemt_user_octets_to_client{user="hello"} 23719498024 (22.09 GB)
telemt_user_unique_ips_current{user="hello"} 24
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 22491.2 (6h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74569
telemt_connections_bad_total 1100
telemt_handshake_timeouts_total 670
telemt_upstream_connect_attempt_total 14310
telemt_upstream_connect_success_total 14239
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 14239
telemt_upstream_connect_attempts_per_request{bucket="2"} 35
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8834
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5404
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 148
telemt_me_reconnect_attempts_total 1953
telemt_me_reconnect_success_total 1956
telemt_me_reader_eof_total 1965
telemt_me_idle_close_by_peer_total 1965
telemt_me_route_drop_no_conn_total 24686
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 93
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 73
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 46
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 7
telemt_pool_force_close_total 157
telemt_me_writer_removed_unexpected_total 1965
telemt_me_writer_restored_same_endpoint_total 1935
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 69552
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 631888360 (602.62 MB)
telemt_user_octets_to_client{user="hello"} 24762801780 (23.06 GB)
telemt_user_unique_ips_current{user="hello"} 24
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 22490.0 (6h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 170869
telemt_connections_bad_total 119
telemt_handshake_timeouts_total 78009
telemt_upstream_connect_attempt_total 33941
telemt_upstream_connect_success_total 33734
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 33734
telemt_upstream_connect_attempts_per_request{bucket="2"} 97
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19727
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13924
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_timeout_total 440
telemt_me_reconnect_attempts_total 16971
telemt_me_reconnect_success_total 16965
telemt_me_reader_eof_total 17992
telemt_me_idle_close_by_peer_total 17991
telemt_me_route_drop_no_conn_total 45171
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 96
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 123
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 92
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 2
telemt_pool_force_close_total 60
telemt_pool_stale_pick_total 2610
telemt_me_writer_removed_unexpected_total 18000
telemt_me_writer_restored_same_endpoint_total 16941
telemt_me_writer_removed_unexpected_minus_restored_total 1059
telemt_user_connections_total{user="hello"} 89469
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 525675544 (501.32 MB)
telemt_user_octets_to_client{user="hello"} 20338150776 (18.94 GB)
telemt_user_unique_ips_current{user="hello"} 25
```