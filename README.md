# Server Metrics 2026-03-04 04:37:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 26795.8 (7h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 182372
telemt_connections_bad_total 1629
telemt_handshake_timeouts_total 3280
telemt_upstream_connect_attempt_total 19494
telemt_upstream_connect_success_total 19408
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 19408
telemt_upstream_connect_attempts_per_request{bucket="2"} 38
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10979
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8404
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 206
telemt_me_reconnect_attempts_total 4467
telemt_me_reconnect_success_total 4451
telemt_me_reader_eof_total 4556
telemt_me_idle_close_by_peer_total 4556
telemt_me_route_drop_no_conn_total 60288
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 109
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 497
telemt_desync_full_logged_total 173
telemt_desync_suppressed_total 324
telemt_desync_frames_bucket_total{bucket="1_2"} 132
telemt_desync_frames_bucket_total{bucket="3_10"} 171
telemt_desync_frames_bucket_total{bucket="gt_10"} 194
telemt_pool_swap_total 5
telemt_pool_force_close_total 168
telemt_me_writer_removed_unexpected_total 4556
telemt_me_writer_restored_same_endpoint_total 4431
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 173045
telemt_user_connections_current{user="hello"} 571
telemt_user_octets_from_client{user="hello"} 1833058840 (1.71 GB)
telemt_user_octets_to_client{user="hello"} 55537464264 (51.72 GB)
telemt_user_unique_ips_current{user="hello"} 59
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 26792.5 (7h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84842
telemt_connections_bad_total 350
telemt_handshake_timeouts_total 20711
telemt_upstream_connect_attempt_total 62525
telemt_upstream_connect_success_total 61867
telemt_upstream_connect_fail_total 313
telemt_upstream_connect_attempts_per_request{bucket="1"} 61861
telemt_upstream_connect_attempts_per_request{bucket="2"} 319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19701
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 313
telemt_me_keepalive_timeout_total 960
telemt_me_reconnect_attempts_total 38737
telemt_me_reconnect_success_total 38710
telemt_me_reader_eof_total 39692
telemt_me_idle_close_by_peer_total 39691
telemt_me_route_drop_no_conn_total 27115
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 116
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 194
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 114
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 102
telemt_desync_frames_bucket_total{bucket="gt_10"} 50
telemt_pool_swap_total 1
telemt_pool_force_close_total 75
telemt_me_writer_removed_unexpected_total 39753
telemt_me_writer_restored_same_endpoint_total 38689
telemt_me_writer_removed_unexpected_minus_restored_total 1064
telemt_user_connections_total{user="hello"} 62476
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 589685868 (562.37 MB)
telemt_user_octets_to_client{user="hello"} 28514591960 (26.56 GB)
telemt_user_unique_ips_current{user="hello"} 20
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 26791.2 (7h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194088
telemt_connections_bad_total 70643
telemt_handshake_timeouts_total 4299
telemt_upstream_connect_attempt_total 34943
telemt_upstream_connect_success_total 34714
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 34714
telemt_upstream_connect_attempts_per_request{bucket="2"} 106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14183
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 468
telemt_me_reconnect_attempts_total 14086
telemt_me_reconnect_success_total 14050
telemt_me_reader_eof_total 14787
telemt_me_idle_close_by_peer_total 14784
telemt_me_route_drop_no_conn_total 38915
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 114
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 309
telemt_desync_full_logged_total 109
telemt_desync_suppressed_total 200
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 111
telemt_desync_frames_bucket_total{bucket="gt_10"} 130
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 14795
telemt_me_writer_restored_same_endpoint_total 14029
telemt_me_writer_removed_unexpected_minus_restored_total 766
telemt_user_connections_total{user="hello"} 115232
telemt_user_connections_current{user="hello"} 272
telemt_user_octets_from_client{user="hello"} 744674000 (710.18 MB)
telemt_user_octets_to_client{user="hello"} 29558255332 (27.53 GB)
telemt_user_unique_ips_current{user="hello"} 24
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 26790.2 (7h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97133
telemt_connections_bad_total 4882
telemt_handshake_timeouts_total 1061
telemt_upstream_connect_attempt_total 18133
telemt_upstream_connect_success_total 18054
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 18054
telemt_upstream_connect_attempts_per_request{bucket="2"} 39
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11187
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6866
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 188
telemt_me_reconnect_attempts_total 2840
telemt_me_reconnect_success_total 2840
telemt_me_reader_eof_total 2862
telemt_me_idle_close_by_peer_total 2862
telemt_me_route_drop_no_conn_total 31822
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 111
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 110
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 64
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_pool_swap_total 8
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 2862
telemt_me_writer_restored_same_endpoint_total 2819
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 87077
telemt_user_connections_current{user="hello"} 201
telemt_user_octets_from_client{user="hello"} 731767648 (697.87 MB)
telemt_user_octets_to_client{user="hello"} 29107051744 (27.11 GB)
telemt_user_unique_ips_current{user="hello"} 21
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 26788.7 (7h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 212794
telemt_connections_bad_total 4330
telemt_handshake_timeouts_total 96984
telemt_upstream_connect_attempt_total 39514
telemt_upstream_connect_success_total 39241
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 39241
telemt_upstream_connect_attempts_per_request{bucket="2"} 127
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23082
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16057
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_timeout_total 550
telemt_me_reconnect_attempts_total 19318
telemt_me_reconnect_success_total 19310
telemt_me_reader_eof_total 20429
telemt_me_idle_close_by_peer_total 20428
telemt_me_route_drop_no_conn_total 50632
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 114
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 156
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 110
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 80
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 3
telemt_pool_force_close_total 86
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 20441
telemt_me_writer_restored_same_endpoint_total 19286
telemt_me_writer_removed_unexpected_minus_restored_total 1155
telemt_user_connections_total{user="hello"} 107679
telemt_user_connections_current{user="hello"} 282
telemt_user_octets_from_client{user="hello"} 699349020 (666.95 MB)
telemt_user_octets_to_client{user="hello"} 24883535848 (23.17 GB)
telemt_user_unique_ips_current{user="hello"} 35
```