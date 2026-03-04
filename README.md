# Server Metrics 2026-03-04 02:13:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 18197.3 (5h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117973
telemt_connections_bad_total 1377
telemt_handshake_timeouts_total 1003
telemt_upstream_connect_attempt_total 15005
telemt_upstream_connect_success_total 14944
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 14944
telemt_upstream_connect_attempts_per_request{bucket="2"} 26
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8454
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6470
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 154
telemt_me_reconnect_attempts_total 4043
telemt_me_reconnect_success_total 4037
telemt_me_reader_eof_total 4129
telemt_me_idle_close_by_peer_total 4129
telemt_me_route_drop_no_conn_total 42549
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 190
telemt_desync_full_logged_total 64
telemt_desync_suppressed_total 126
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_pool_swap_total 3
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 4129
telemt_me_writer_restored_same_endpoint_total 4017
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 112926
telemt_user_connections_current{user="hello"} 310
telemt_user_octets_from_client{user="hello"} 904857760 (862.94 MB)
telemt_user_octets_to_client{user="hello"} 33814450100 (31.49 GB)
telemt_user_unique_ips_current{user="hello"} 56
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 18194.1 (5h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55174
telemt_connections_bad_total 271
telemt_handshake_timeouts_total 13973
telemt_upstream_connect_attempt_total 41346
telemt_upstream_connect_success_total 40903
telemt_upstream_connect_fail_total 204
telemt_upstream_connect_attempts_per_request{bucket="1"} 40897
telemt_upstream_connect_attempts_per_request{bucket="2"} 210
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27854
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13030
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 204
telemt_me_keepalive_timeout_total 768
telemt_me_reconnect_attempts_total 24889
telemt_me_reconnect_success_total 24872
telemt_me_reader_eof_total 25503
telemt_me_idle_close_by_peer_total 25502
telemt_me_route_drop_no_conn_total 18680
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 81
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 80
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_me_writer_removed_unexpected_total 25564
telemt_me_writer_restored_same_endpoint_total 24852
telemt_me_writer_removed_unexpected_minus_restored_total 712
telemt_user_connections_total{user="hello"} 40266
telemt_user_connections_current{user="hello"} 212
telemt_user_octets_from_client{user="hello"} 320623120 (305.77 MB)
telemt_user_octets_to_client{user="hello"} 22972841908 (21.40 GB)
telemt_user_unique_ips_current{user="hello"} 25
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 18192.8 (5h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130105
telemt_connections_bad_total 46045
telemt_handshake_timeouts_total 3159
telemt_upstream_connect_attempt_total 20698
telemt_upstream_connect_success_total 20573
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 20573
telemt_upstream_connect_attempts_per_request{bucket="2"} 56
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12051
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8456
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 257
telemt_me_reconnect_attempts_total 6912
telemt_me_reconnect_success_total 6901
telemt_me_reader_eof_total 7191
telemt_me_idle_close_by_peer_total 7189
telemt_me_route_drop_no_conn_total 24627
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 79
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 264
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 174
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 115
telemt_pool_swap_total 2
telemt_pool_force_close_total 62
telemt_me_writer_removed_unexpected_total 7192
telemt_me_writer_restored_same_endpoint_total 6880
telemt_me_writer_removed_unexpected_minus_restored_total 312
telemt_user_connections_total{user="hello"} 77873
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 479425472 (457.22 MB)
telemt_user_octets_to_client{user="hello"} 19446749832 (18.11 GB)
telemt_user_unique_ips_current{user="hello"} 20
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 18191.8 (5h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58089
telemt_connections_bad_total 181
telemt_handshake_timeouts_total 592
telemt_upstream_connect_attempt_total 11228
telemt_upstream_connect_success_total 11174
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 11174
telemt_upstream_connect_attempts_per_request{bucket="2"} 26
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6984
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4189
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 115
telemt_me_reconnect_attempts_total 1537
telemt_me_reconnect_success_total 1544
telemt_me_reader_eof_total 1549
telemt_me_idle_close_by_peer_total 1549
telemt_me_route_drop_no_conn_total 19615
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 77
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 17
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 6
telemt_pool_force_close_total 139
telemt_me_writer_removed_unexpected_total 1549
telemt_me_writer_restored_same_endpoint_total 1524
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 56275
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 463257928 (441.80 MB)
telemt_user_octets_to_client{user="hello"} 18372078792 (17.11 GB)
telemt_user_unique_ips_current{user="hello"} 23
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 18190.4 (5h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139784
telemt_connections_bad_total 71
telemt_handshake_timeouts_total 62339
telemt_upstream_connect_attempt_total 26647
telemt_upstream_connect_success_total 26477
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 26477
telemt_upstream_connect_attempts_per_request{bucket="2"} 81
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 354
telemt_me_reconnect_attempts_total 13687
telemt_me_reconnect_success_total 13687
telemt_me_reader_eof_total 14557
telemt_me_idle_close_by_peer_total 14556
telemt_me_route_drop_no_conn_total 40407
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 78
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 106
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 81
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 51
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 2
telemt_pool_force_close_total 59
telemt_pool_stale_pick_total 1805
telemt_me_writer_removed_unexpected_total 14562
telemt_me_writer_restored_same_endpoint_total 13663
telemt_me_writer_removed_unexpected_minus_restored_total 899
telemt_user_connections_total{user="hello"} 74742
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 375875556 (358.46 MB)
telemt_user_octets_to_client{user="hello"} 16918440576 (15.76 GB)
telemt_user_unique_ips_current{user="hello"} 19
```