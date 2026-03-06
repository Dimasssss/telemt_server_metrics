# Server Metrics 2026-03-06 03:41:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 19226.0 (5h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132663
telemt_connections_bad_total 15926
telemt_handshake_timeouts_total 2749
telemt_upstream_connect_attempt_total 21136
telemt_upstream_connect_success_total 20959
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 20959
telemt_upstream_connect_attempts_per_request{bucket="2"} 83
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12765
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8156
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 218
telemt_me_reconnect_attempts_total 7749
telemt_me_reconnect_success_total 7723
telemt_me_reader_eof_total 7997
telemt_me_idle_close_by_peer_total 7997
telemt_me_route_drop_no_conn_total 36308
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 344
telemt_desync_full_logged_total 118
telemt_desync_suppressed_total 226
telemt_desync_frames_bucket_total{bucket="1_2"} 86
telemt_desync_frames_bucket_total{bucket="3_10"} 124
telemt_desync_frames_bucket_total{bucket="gt_10"} 134
telemt_pool_swap_total 2
telemt_pool_force_close_total 93
telemt_me_writer_removed_unexpected_total 7997
telemt_me_writer_restored_same_endpoint_total 7717
telemt_me_writer_removed_unexpected_minus_restored_total 280
telemt_user_connections_total{user="hello"} 106763
telemt_user_connections_current{user="hello"} 464
telemt_user_octets_from_client{user="hello"} 1388721556 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 41787481988 (38.92 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 19221.4 (5h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44708
telemt_connections_bad_total 105
telemt_handshake_timeouts_total 581
telemt_upstream_connect_attempt_total 15369
telemt_upstream_connect_success_total 15367
telemt_upstream_connect_attempts_per_request{bucket="1"} 15367
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8643
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6719
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 193
telemt_me_reconnect_attempts_total 2787
telemt_me_reconnect_success_total 2773
telemt_me_reader_eof_total 2810
telemt_me_idle_close_by_peer_total 2810
telemt_me_route_drop_no_conn_total 13265
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 136
telemt_desync_full_logged_total 51
telemt_desync_suppressed_total 85
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 57
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 6
telemt_pool_force_close_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 2811
telemt_me_writer_restored_same_endpoint_total 2767
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 43231
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 306486104 (292.29 MB)
telemt_user_octets_to_client{user="hello"} 10556028216 (9.83 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 19218.8 (5h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79068
telemt_connections_bad_total 785
telemt_handshake_timeouts_total 1602
telemt_upstream_connect_attempt_total 18881
telemt_upstream_connect_success_total 18733
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 18733
telemt_upstream_connect_attempts_per_request{bucket="2"} 65
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7678
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 228
telemt_me_reconnect_attempts_total 5845
telemt_me_reconnect_success_total 5824
telemt_me_reader_eof_total 6093
telemt_me_idle_close_by_peer_total 6093
telemt_me_route_drop_no_conn_total 21924
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 82
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 173
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 94
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 6097
telemt_me_writer_restored_same_endpoint_total 5816
telemt_me_writer_removed_unexpected_minus_restored_total 281
telemt_user_connections_total{user="hello"} 73908
telemt_user_connections_current{user="hello"} 226
telemt_user_octets_from_client{user="hello"} 737616372 (703.45 MB)
telemt_user_octets_to_client{user="hello"} 24878271472 (23.17 GB)
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 19215.4 (5h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65069
telemt_connections_bad_total 684
telemt_handshake_timeouts_total 4087
telemt_upstream_connect_attempt_total 12861
telemt_upstream_connect_success_total 12820
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 12820
telemt_upstream_connect_attempts_per_request{bucket="2"} 20
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7501
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5318
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 2606
telemt_me_reconnect_success_total 2588
telemt_me_reader_eof_total 2690
telemt_me_idle_close_by_peer_total 2690
telemt_me_route_drop_no_conn_total 23720
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 7
telemt_pool_force_close_total 148
telemt_me_writer_removed_unexpected_total 2690
telemt_me_writer_restored_same_endpoint_total 2581
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 56828
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 581988472 (555.03 MB)
telemt_user_octets_to_client{user="hello"} 25390989308 (23.65 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 19214.4 (5h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77692
telemt_connections_bad_total 871
telemt_handshake_timeouts_total 523
telemt_upstream_connect_attempt_total 12587
telemt_upstream_connect_success_total 12561
telemt_upstream_connect_attempts_per_request{bucket="1"} 12561
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4844
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 162
telemt_me_reconnect_attempts_total 1715
telemt_me_reconnect_success_total 1708
telemt_me_reader_eof_total 1754
telemt_me_idle_close_by_peer_total 1754
telemt_me_route_drop_no_conn_total 24955
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 78
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 6
telemt_pool_force_close_total 92
telemt_me_writer_removed_unexpected_total 1755
telemt_me_writer_restored_same_endpoint_total 1702
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 75166
telemt_user_connections_current{user="hello"} 255
telemt_user_octets_from_client{user="hello"} 12800554812 (11.92 GB)
telemt_user_octets_to_client{user="hello"} 44322093020 (41.28 GB)
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 33
```