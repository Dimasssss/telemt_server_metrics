# Server Metrics 2026-03-06 07:01:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 31204.9 (8h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 298783
telemt_connections_bad_total 16126
telemt_handshake_timeouts_total 3869
telemt_upstream_connect_attempt_total 31159
telemt_upstream_connect_success_total 30864
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 30864
telemt_upstream_connect_attempts_per_request{bucket="2"} 131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19005
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11785
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_timeout_total 318
telemt_me_reconnect_attempts_total 10815
telemt_me_reconnect_success_total 10771
telemt_me_reader_eof_total 11137
telemt_me_idle_close_by_peer_total 11137
telemt_me_route_drop_no_conn_total 102071
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 130
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1023
telemt_desync_full_logged_total 312
telemt_desync_suppressed_total 711
telemt_desync_frames_bucket_total{bucket="1_2"} 274
telemt_desync_frames_bucket_total{bucket="3_10"} 347
telemt_desync_frames_bucket_total{bucket="gt_10"} 402
telemt_pool_swap_total 4
telemt_pool_force_close_total 208
telemt_me_writer_removed_unexpected_total 11139
telemt_me_writer_restored_same_endpoint_total 10765
telemt_me_writer_removed_unexpected_minus_restored_total 374
telemt_user_connections_total{user="hello"} 262058
telemt_user_connections_current{user="hello"} 866
telemt_user_octets_from_client{user="hello"} 9153929944 (8.53 GB)
telemt_user_octets_to_client{user="hello"} 96145601708 (89.54 GB)
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 31200.3 (8h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127251
telemt_connections_bad_total 171
telemt_handshake_timeouts_total 13909
telemt_upstream_connect_attempt_total 25753
telemt_upstream_connect_success_total 25751
telemt_upstream_connect_attempts_per_request{bucket="1"} 25751
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11263
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 310
telemt_me_reconnect_attempts_total 6793
telemt_me_reconnect_success_total 6764
telemt_me_reader_eof_total 6915
telemt_me_idle_close_by_peer_total 6915
telemt_me_route_drop_no_conn_total 36366
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 133
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 401
telemt_desync_full_logged_total 133
telemt_desync_suppressed_total 268
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 151
telemt_desync_frames_bucket_total{bucket="gt_10"} 133
telemt_pool_swap_total 10
telemt_pool_force_close_total 197
telemt_pool_stale_pick_total 2124
telemt_me_writer_removed_unexpected_total 6916
telemt_me_writer_restored_same_endpoint_total 6757
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 110880
telemt_user_connections_current{user="hello"} 395
telemt_user_octets_from_client{user="hello"} 1280854852 (1.19 GB)
telemt_user_octets_to_client{user="hello"} 36009014220 (33.54 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 31197.8 (8h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 215526
telemt_connections_bad_total 1773
telemt_handshake_timeouts_total 5656
telemt_upstream_connect_attempt_total 36404
telemt_upstream_connect_success_total 36147
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 36147
telemt_upstream_connect_attempts_per_request{bucket="2"} 116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14616
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_keepalive_timeout_total 515
telemt_me_reconnect_attempts_total 14112
telemt_me_reconnect_success_total 14072
telemt_me_reader_eof_total 14725
telemt_me_idle_close_by_peer_total 14723
telemt_me_route_drop_no_conn_total 64633
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 127
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 431
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 288
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 153
telemt_desync_frames_bucket_total{bucket="gt_10"} 186
telemt_pool_swap_total 5
telemt_pool_force_close_total 173
telemt_pool_stale_pick_total 82
telemt_me_writer_removed_unexpected_total 14753
telemt_me_writer_restored_same_endpoint_total 14050
telemt_me_writer_restored_fallback_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 689
telemt_user_connections_total{user="hello"} 191675
telemt_user_connections_current{user="hello"} 625
telemt_user_octets_from_client{user="hello"} 1955481140 (1.82 GB)
telemt_user_octets_to_client{user="hello"} 61910767744 (57.66 GB)
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 31194.5 (8h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 170519
telemt_connections_bad_total 19292
telemt_handshake_timeouts_total 6598
telemt_upstream_connect_attempt_total 22083
telemt_upstream_connect_success_total 22008
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 22008
telemt_upstream_connect_attempts_per_request{bucket="2"} 36
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13190
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8816
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 240
telemt_me_reconnect_attempts_total 4890
telemt_me_reconnect_success_total 4857
telemt_me_reader_eof_total 5028
telemt_me_idle_close_by_peer_total 5028
telemt_me_route_drop_no_conn_total 54326
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 126
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 412
telemt_desync_full_logged_total 130
telemt_desync_suppressed_total 282
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 159
telemt_desync_frames_bucket_total{bucket="gt_10"} 174
telemt_pool_swap_total 10
telemt_pool_force_close_total 244
telemt_me_writer_removed_unexpected_total 5029
telemt_me_writer_restored_same_endpoint_total 4850
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 138097
telemt_user_connections_current{user="hello"} 384
telemt_user_octets_from_client{user="hello"} 1992931380 (1.86 GB)
telemt_user_octets_to_client{user="hello"} 46350444624 (43.17 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 31193.4 (8h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 184381
telemt_connections_bad_total 3279
telemt_handshake_timeouts_total 1067
telemt_upstream_connect_attempt_total 20993
telemt_upstream_connect_success_total 20945
telemt_upstream_connect_attempts_per_request{bucket="1"} 20945
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8458
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 321
telemt_me_reconnect_attempts_total 3712
telemt_me_reconnect_success_total 3694
telemt_me_reader_eof_total 3812
telemt_me_idle_close_by_peer_total 3811
telemt_me_route_drop_no_conn_total 71086
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 133
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 407
telemt_desync_full_logged_total 163
telemt_desync_suppressed_total 244
telemt_desync_frames_bucket_total{bucket="1_2"} 71
telemt_desync_frames_bucket_total{bucket="3_10"} 189
telemt_desync_frames_bucket_total{bucket="gt_10"} 147
telemt_pool_swap_total 10
telemt_pool_force_close_total 208
telemt_pool_stale_pick_total 5
telemt_me_writer_removed_unexpected_total 3827
telemt_me_writer_restored_same_endpoint_total 3687
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 176588
telemt_user_connections_current{user="hello"} 474
telemt_user_octets_from_client{user="hello"} 24397160412 (22.72 GB)
telemt_user_octets_to_client{user="hello"} 107008086440 (99.66 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 93
```