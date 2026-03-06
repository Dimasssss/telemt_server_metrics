# Server Metrics 2026-03-06 05:19:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 25062.3 (6h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194920
telemt_connections_bad_total 16006
telemt_handshake_timeouts_total 3219
telemt_upstream_connect_attempt_total 26610
telemt_upstream_connect_success_total 26397
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 26397
telemt_upstream_connect_attempts_per_request{bucket="2"} 101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10183
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_timeout_total 272
telemt_me_reconnect_attempts_total 9710
telemt_me_reconnect_success_total 9675
telemt_me_reader_eof_total 10008
telemt_me_idle_close_by_peer_total 10008
telemt_me_route_drop_no_conn_total 60582
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 106
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 593
telemt_desync_full_logged_total 189
telemt_desync_suppressed_total 404
telemt_desync_frames_bucket_total{bucket="1_2"} 167
telemt_desync_frames_bucket_total{bucket="3_10"} 214
telemt_desync_frames_bucket_total{bucket="gt_10"} 212
telemt_pool_swap_total 3
telemt_pool_force_close_total 153
telemt_me_writer_removed_unexpected_total 10009
telemt_me_writer_restored_same_endpoint_total 9669
telemt_me_writer_removed_unexpected_minus_restored_total 340
telemt_user_connections_total{user="hello"} 167028
telemt_user_connections_current{user="hello"} 621
telemt_user_octets_from_client{user="hello"} 3639789800 (3.39 GB)
telemt_user_octets_to_client{user="hello"} 64512318760 (60.08 GB)
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 25057.7 (6h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73711
telemt_connections_bad_total 147
telemt_handshake_timeouts_total 1535
telemt_upstream_connect_attempt_total 23901
telemt_upstream_connect_success_total 23899
telemt_upstream_connect_attempts_per_request{bucket="1"} 23899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13605
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10286
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 288
telemt_me_reconnect_attempts_total 6758
telemt_me_reconnect_success_total 6736
telemt_me_reader_eof_total 6886
telemt_me_idle_close_by_peer_total 6886
telemt_me_route_drop_no_conn_total 22000
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 108
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 291
telemt_desync_full_logged_total 97
telemt_desync_suppressed_total 194
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 104
telemt_desync_frames_bucket_total{bucket="gt_10"} 103
telemt_pool_swap_total 7
telemt_pool_force_close_total 125
telemt_pool_stale_pick_total 1958
telemt_me_writer_removed_unexpected_total 6887
telemt_me_writer_restored_same_endpoint_total 6730
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 70615
telemt_user_connections_current{user="hello"} 298
telemt_user_octets_from_client{user="hello"} 663953736 (633.20 MB)
telemt_user_octets_to_client{user="hello"} 19446074940 (18.11 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 25055.1 (6h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127663
telemt_connections_bad_total 1438
telemt_handshake_timeouts_total 3160
telemt_upstream_connect_attempt_total 24782
telemt_upstream_connect_success_total 24593
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 24593
telemt_upstream_connect_attempts_per_request{bucket="2"} 85
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14826
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9726
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 305
telemt_me_reconnect_attempts_total 7913
telemt_me_reconnect_success_total 7885
telemt_me_reader_eof_total 8226
telemt_me_idle_close_by_peer_total 8226
telemt_me_route_drop_no_conn_total 37055
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 105
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 238
telemt_desync_full_logged_total 74
telemt_desync_suppressed_total 164
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 72
telemt_desync_frames_bucket_total{bucket="gt_10"} 121
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 8231
telemt_me_writer_restored_same_endpoint_total 7877
telemt_me_writer_removed_unexpected_minus_restored_total 354
telemt_user_connections_total{user="hello"} 119421
telemt_user_connections_current{user="hello"} 406
telemt_user_octets_from_client{user="hello"} 1111879808 (1.04 GB)
telemt_user_octets_to_client{user="hello"} 40459065112 (37.68 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 25051.9 (6h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103209
telemt_connections_bad_total 6071
telemt_handshake_timeouts_total 5600
telemt_upstream_connect_attempt_total 17631
telemt_upstream_connect_success_total 17572
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 17572
telemt_upstream_connect_attempts_per_request{bucket="2"} 29
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10425
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7146
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 190
telemt_me_reconnect_attempts_total 3562
telemt_me_reconnect_success_total 3534
telemt_me_reader_eof_total 3655
telemt_me_idle_close_by_peer_total 3655
telemt_me_route_drop_no_conn_total 35575
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 102
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 266
telemt_desync_full_logged_total 91
telemt_desync_suppressed_total 175
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 89
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 8
telemt_pool_force_close_total 169
telemt_me_writer_removed_unexpected_total 3655
telemt_me_writer_restored_same_endpoint_total 3527
telemt_me_writer_removed_unexpected_minus_restored_total 128
telemt_user_connections_total{user="hello"} 86947
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 1502049016 (1.40 GB)
telemt_user_octets_to_client{user="hello"} 33088051204 (30.82 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 25050.7 (6h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117955
telemt_connections_bad_total 1016
telemt_handshake_timeouts_total 669
telemt_upstream_connect_attempt_total 16773
telemt_upstream_connect_success_total 16734
telemt_upstream_connect_attempts_per_request{bucket="1"} 16734
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6745
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 2854
telemt_me_reconnect_success_total 2841
telemt_me_reader_eof_total 2941
telemt_me_idle_close_by_peer_total 2940
telemt_me_route_drop_no_conn_total 41029
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 107
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 160
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 76
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 90
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 8
telemt_pool_force_close_total 155
telemt_me_writer_removed_unexpected_total 2945
telemt_me_writer_restored_same_endpoint_total 2834
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 114205
telemt_user_connections_current{user="hello"} 372
telemt_user_octets_from_client{user="hello"} 23660675952 (22.04 GB)
telemt_user_octets_to_client{user="hello"} 69313571164 (64.55 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 62
```