# Server Metrics 2026-03-04 02:08:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 17890.8 (4h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116293
telemt_connections_bad_total 1375
telemt_handshake_timeouts_total 998
telemt_upstream_connect_attempt_total 14882
telemt_upstream_connect_success_total 14821
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 14821
telemt_upstream_connect_attempts_per_request{bucket="2"} 26
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8384
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6417
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 154
telemt_me_reconnect_attempts_total 4038
telemt_me_reconnect_success_total 4033
telemt_me_reader_eof_total 4125
telemt_me_idle_close_by_peer_total 4125
telemt_me_route_drop_no_conn_total 42096
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 72
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 170
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 110
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 3
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 4125
telemt_me_writer_restored_same_endpoint_total 4013
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 111285
telemt_user_connections_current{user="hello"} 345
telemt_user_octets_from_client{user="hello"} 896749236 (855.21 MB)
telemt_user_octets_to_client{user="hello"} 33528488936 (31.23 GB)
telemt_user_unique_ips_current{user="hello"} 48
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 17887.3 (4h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54096
telemt_connections_bad_total 194
telemt_handshake_timeouts_total 13611
telemt_upstream_connect_attempt_total 40366
telemt_upstream_connect_success_total 39932
telemt_upstream_connect_fail_total 201
telemt_upstream_connect_attempts_per_request{bucket="1"} 39926
telemt_upstream_connect_attempts_per_request{bucket="2"} 207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12698
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 201
telemt_me_keepalive_timeout_total 759
telemt_me_reconnect_attempts_total 24217
telemt_me_reconnect_success_total 24201
telemt_me_reader_eof_total 24820
telemt_me_idle_close_by_peer_total 24819
telemt_me_route_drop_no_conn_total 18390
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 78
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 79
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 31
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_me_writer_removed_unexpected_total 24881
telemt_me_writer_restored_same_endpoint_total 24181
telemt_me_writer_removed_unexpected_minus_restored_total 700
telemt_user_connections_total{user="hello"} 39670
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 306350344 (292.16 MB)
telemt_user_octets_to_client{user="hello"} 22874919972 (21.30 GB)
telemt_user_unique_ips_current{user="hello"} 26
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 17885.9 (4h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128133
telemt_connections_bad_total 45240
telemt_handshake_timeouts_total 3154
telemt_upstream_connect_attempt_total 20293
telemt_upstream_connect_success_total 20176
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 20176
telemt_upstream_connect_attempts_per_request{bucket="2"} 53
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11812
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8299
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 250
telemt_me_reconnect_attempts_total 6795
telemt_me_reconnect_success_total 6784
telemt_me_reader_eof_total 7070
telemt_me_idle_close_by_peer_total 7068
telemt_me_route_drop_no_conn_total 24359
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 262
telemt_desync_full_logged_total 88
telemt_desync_suppressed_total 174
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 114
telemt_pool_swap_total 2
telemt_pool_force_close_total 62
telemt_me_writer_removed_unexpected_total 7071
telemt_me_writer_restored_same_endpoint_total 6763
telemt_me_writer_removed_unexpected_minus_restored_total 308
telemt_user_connections_total{user="hello"} 76933
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 475758212 (453.72 MB)
telemt_user_octets_to_client{user="hello"} 19275678012 (17.95 GB)
telemt_user_unique_ips_current{user="hello"} 24
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 17884.9 (4h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57034
telemt_connections_bad_total 181
telemt_handshake_timeouts_total 548
telemt_upstream_connect_attempt_total 11077
telemt_upstream_connect_success_total 11028
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 11028
telemt_upstream_connect_attempts_per_request{bucket="2"} 24
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4140
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 114
telemt_me_reconnect_attempts_total 1537
telemt_me_reconnect_success_total 1544
telemt_me_reader_eof_total 1549
telemt_me_idle_close_by_peer_total 1549
telemt_me_route_drop_no_conn_total 19469
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 74
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
telemt_user_connections_total{user="hello"} 55290
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 456539716 (435.39 MB)
telemt_user_octets_to_client{user="hello"} 18284440368 (17.03 GB)
telemt_user_unique_ips_current{user="hello"} 29
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 17883.5 (4h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137728
telemt_connections_bad_total 71
telemt_handshake_timeouts_total 61293
telemt_upstream_connect_attempt_total 26268
telemt_upstream_connect_success_total 26104
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 26104
telemt_upstream_connect_attempts_per_request{bucket="2"} 78
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14991
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11055
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_keepalive_timeout_total 352
telemt_me_reconnect_attempts_total 13568
telemt_me_reconnect_success_total 13568
telemt_me_reader_eof_total 14432
telemt_me_idle_close_by_peer_total 14431
telemt_me_route_drop_no_conn_total 40060
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 103
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 79
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 51
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 2
telemt_pool_force_close_total 59
telemt_pool_stale_pick_total 1709
telemt_me_writer_removed_unexpected_total 14437
telemt_me_writer_restored_same_endpoint_total 13544
telemt_me_writer_removed_unexpected_minus_restored_total 893
telemt_user_connections_total{user="hello"} 73781
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 371993900 (354.76 MB)
telemt_user_octets_to_client{user="hello"} 16820789676 (15.67 GB)
telemt_user_unique_ips_current{user="hello"} 20
```