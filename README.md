# Server Metrics 2026-03-06 13:52:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 12609.0 (3h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 379060
telemt_connections_bad_total 1728
telemt_handshake_timeouts_total 2052
telemt_upstream_connect_attempt_total 5963
telemt_upstream_connect_success_total 5924
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 5938
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3251
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2639
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 66
telemt_me_reconnect_attempts_total 1015
telemt_me_reconnect_success_total 1007
telemt_me_reader_eof_total 1065
telemt_me_idle_close_by_peer_total 1065
telemt_me_route_drop_no_conn_total 125905
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 2046
telemt_desync_full_logged_total 488
telemt_desync_suppressed_total 1558
telemt_desync_frames_bucket_total{bucket="1_2"} 472
telemt_desync_frames_bucket_total{bucket="3_10"} 699
telemt_desync_frames_bucket_total{bucket="gt_10"} 875
telemt_pool_swap_total 2
telemt_pool_force_close_total 83
telemt_me_writer_removed_unexpected_total 1065
telemt_me_writer_restored_same_endpoint_total 1001
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 313896
telemt_user_connections_current{user="hello"} 1181
telemt_user_octets_from_client{user="hello"} 5928981796 (5.52 GB)
telemt_user_octets_to_client{user="hello"} 130790462736 (121.81 GB)
telemt_user_unique_ips_current{user="hello"} 303
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 12608.9 (3h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141834
telemt_connections_bad_total 817
telemt_handshake_timeouts_total 4398
telemt_upstream_connect_attempt_total 5785
telemt_upstream_connect_success_total 5770
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 5785
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3068
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 82
telemt_me_reconnect_attempts_total 592
telemt_me_reconnect_success_total 584
telemt_me_reader_eof_total 623
telemt_me_idle_close_by_peer_total 623
telemt_me_route_drop_no_conn_total 64244
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 504
telemt_desync_full_logged_total 169
telemt_desync_suppressed_total 335
telemt_desync_frames_bucket_total{bucket="1_2"} 78
telemt_desync_frames_bucket_total{bucket="3_10"} 185
telemt_desync_frames_bucket_total{bucket="gt_10"} 241
telemt_pool_swap_total 3
telemt_pool_force_close_total 94
telemt_me_writer_removed_unexpected_total 623
telemt_me_writer_restored_same_endpoint_total 584
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 129122
telemt_user_connections_current{user="hello"} 451
telemt_user_octets_from_client{user="hello"} 1418060908 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 60932703500 (56.75 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 12608.8 (3h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 300359
telemt_connections_bad_total 5036
telemt_handshake_timeouts_total 29530
telemt_upstream_connect_attempt_total 7878
telemt_upstream_connect_success_total 7840
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 7871
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4197
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3628
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 1945
telemt_me_reconnect_success_total 1936
telemt_me_reader_eof_total 2041
telemt_me_idle_close_by_peer_total 2041
telemt_me_route_drop_no_conn_total 141082
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 50
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 496
telemt_desync_full_logged_total 141
telemt_desync_suppressed_total 355
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 210
telemt_desync_frames_bucket_total{bucket="gt_10"} 176
telemt_pool_swap_total 1
telemt_pool_force_close_total 83
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 2042
telemt_me_writer_restored_same_endpoint_total 1931
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 255534
telemt_user_connections_current{user="hello"} 741
telemt_user_octets_from_client{user="hello"} 2539010308 (2.36 GB)
telemt_user_octets_to_client{user="hello"} 81777093672 (76.16 GB)
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 11924.7 (3h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 182709
telemt_connections_bad_total 38852
telemt_handshake_timeouts_total 3273
telemt_upstream_connect_attempt_total 5790
telemt_upstream_connect_success_total 5790
telemt_upstream_connect_attempts_per_request{bucket="1"} 5790
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3346
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2444
telemt_me_keepalive_timeout_total 72
telemt_me_reconnect_attempts_total 763
telemt_me_reconnect_success_total 755
telemt_me_reader_eof_total 767
telemt_me_idle_close_by_peer_total 767
telemt_me_route_drop_no_conn_total 70208
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 53
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 228
telemt_desync_full_logged_total 82
telemt_desync_suppressed_total 146
telemt_desync_frames_bucket_total{bucket="1_2"} 62
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 81
telemt_pool_swap_total 3
telemt_pool_force_close_total 135
telemt_me_writer_removed_unexpected_total 767
telemt_me_writer_restored_same_endpoint_total 755
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 130723
telemt_user_connections_current{user="hello"} 556
telemt_user_octets_from_client{user="hello"} 1570302296 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 52765937600 (49.14 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 12609.1 (3h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 229328
telemt_connections_bad_total 7767
telemt_handshake_timeouts_total 2456
telemt_upstream_connect_attempt_total 4715
telemt_upstream_connect_success_total 4707
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4708
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2643
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2035
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 493
telemt_me_reconnect_success_total 485
telemt_me_reader_eof_total 501
telemt_me_idle_close_by_peer_total 501
telemt_me_route_drop_no_conn_total 118154
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 49
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 352
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 229
telemt_desync_frames_bucket_total{bucket="1_2"} 147
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 98
telemt_pool_swap_total 3
telemt_pool_force_close_total 111
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 503
telemt_me_writer_restored_same_endpoint_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 207206
telemt_user_connections_current{user="hello"} 596
telemt_user_octets_from_client{user="hello"} 13950944412 (12.99 GB)
telemt_user_octets_to_client{user="hello"} 118154702124 (110.04 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 73
```