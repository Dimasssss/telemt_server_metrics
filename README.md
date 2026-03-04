# Server Metrics 2026-03-04 22:24:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 5473.1 (1h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62787
telemt_connections_bad_total 1345
telemt_handshake_timeouts_total 433
telemt_upstream_connect_attempt_total 4160
telemt_upstream_connect_success_total 4118
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 4118
telemt_upstream_connect_attempts_per_request{bucket="2"} 16
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2432
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1667
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 57
telemt_me_reconnect_attempts_total 954
telemt_me_reconnect_success_total 966
telemt_me_reader_eof_total 968
telemt_me_idle_close_by_peer_total 968
telemt_me_route_drop_no_conn_total 15481
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 126
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 50
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 968
telemt_me_writer_restored_same_endpoint_total 946
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 52511
telemt_user_connections_current{user="hello"} 421
telemt_user_octets_from_client{user="hello"} 2255417364 (2.10 GB)
telemt_user_octets_to_client{user="hello"} 25864882492 (24.09 GB)
telemt_user_unique_ips_current{user="hello"} 47
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 5467.8 (1h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22803
telemt_connections_bad_total 675
telemt_handshake_timeouts_total 169
telemt_upstream_connect_attempt_total 4602
telemt_upstream_connect_success_total 4553
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 4553
telemt_upstream_connect_attempts_per_request{bucket="2"} 23
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1917
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 42
telemt_me_reconnect_attempts_total 1158
telemt_me_reconnect_success_total 1168
telemt_me_reader_eof_total 1174
telemt_me_idle_close_by_peer_total 1174
telemt_me_route_drop_no_conn_total 6633
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 115
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 65
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 44
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_me_writer_removed_unexpected_total 1174
telemt_me_writer_restored_same_endpoint_total 1149
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 21260
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 186049300 (177.43 MB)
telemt_user_octets_to_client{user="hello"} 5586758404 (5.20 GB)
telemt_user_unique_ips_current{user="hello"} 18
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 5464.5 (1h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51890
telemt_connections_bad_total 966
telemt_handshake_timeouts_total 236
telemt_upstream_connect_attempt_total 1699
telemt_upstream_connect_success_total 1679
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1679
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 948
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 720
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 24
telemt_me_reconnect_success_total 38
telemt_me_reader_eof_total 21
telemt_me_idle_close_by_peer_total 21
telemt_me_route_drop_no_conn_total 15567
telemt_me_single_endpoint_shadow_rotate_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 137
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 94
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 2
telemt_pool_force_close_total 51
telemt_me_writer_removed_unexpected_total 21
telemt_me_writer_restored_same_endpoint_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 47189
telemt_user_connections_current{user="hello"} 347
telemt_user_octets_from_client{user="hello"} 668150992 (637.20 MB)
telemt_user_octets_to_client{user="hello"} 19126105708 (17.81 GB)
telemt_user_unique_ips_current{user="hello"} 34
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 37512.7 (10h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 513625
telemt_connections_bad_total 68275
telemt_handshake_timeouts_total 14654
telemt_upstream_connect_attempt_total 16330
telemt_upstream_connect_success_total 16330
telemt_upstream_connect_attempts_per_request{bucket="1"} 16330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9255
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7074
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 218
telemt_me_reconnect_attempts_total 2161
telemt_me_reconnect_success_total 2146
telemt_me_reader_eof_total 2186
telemt_me_idle_close_by_peer_total 2186
telemt_me_route_drop_no_conn_total 177012
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 151
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 696
telemt_desync_full_logged_total 293
telemt_desync_suppressed_total 403
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 196
telemt_desync_frames_bucket_total{bucket="gt_10"} 282
telemt_pool_swap_total 13
telemt_pool_force_close_total 423
telemt_me_writer_removed_unexpected_total 2187
telemt_me_writer_restored_same_endpoint_total 2122
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 402519
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 5679731768 (5.29 GB)
telemt_user_octets_to_client{user="hello"} 153853197020 (143.29 GB)
telemt_user_unique_ips_current{user="hello"} 27
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 37872.0 (10h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 515512
telemt_connections_bad_total 3759
telemt_handshake_timeouts_total 5746
telemt_upstream_connect_attempt_total 22227
telemt_upstream_connect_success_total 22107
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 22107
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9403
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 314
telemt_me_reconnect_attempts_total 4566
telemt_me_reconnect_success_total 4553
telemt_me_reader_eof_total 4718
telemt_me_idle_close_by_peer_total 4718
telemt_me_route_drop_no_conn_total 227495
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 151
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 826
telemt_desync_full_logged_total 299
telemt_desync_suppressed_total 527
telemt_desync_frames_bucket_total{bucket="1_2"} 167
telemt_desync_frames_bucket_total{bucket="3_10"} 349
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 8
telemt_pool_force_close_total 370
telemt_pool_stale_pick_total 189
telemt_me_writer_removed_unexpected_total 4721
telemt_me_writer_restored_same_endpoint_total 4532
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 465490
telemt_user_connections_current{user="hello"} 288
telemt_user_octets_from_client{user="hello"} 7177522164 (6.68 GB)
telemt_user_octets_to_client{user="hello"} 150021716000 (139.72 GB)
telemt_user_unique_ips_current{user="hello"} 33
```