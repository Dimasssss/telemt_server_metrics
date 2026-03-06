# Server Metrics 2026-03-06 12:04:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 6138.8 (1h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 204293
telemt_connections_bad_total 498
telemt_handshake_timeouts_total 1099
telemt_upstream_connect_attempt_total 2003
telemt_upstream_connect_success_total 1983
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1992
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 839
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 87
telemt_me_reconnect_success_total 89
telemt_me_reader_eof_total 87
telemt_me_idle_close_by_peer_total 87
telemt_me_route_drop_no_conn_total 53009
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 831
telemt_desync_full_logged_total 197
telemt_desync_suppressed_total 634
telemt_desync_frames_bucket_total{bucket="1_2"} 220
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 305
telemt_pool_swap_total 2
telemt_pool_force_close_total 82
telemt_me_writer_removed_unexpected_total 87
telemt_me_writer_restored_same_endpoint_total 83
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 147965
telemt_user_connections_current{user="hello"} 1109
telemt_user_octets_from_client{user="hello"} 3553845296 (3.31 GB)
telemt_user_octets_to_client{user="hello"} 59878534688 (55.77 GB)
telemt_user_unique_ips_current{user="hello"} 289
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 6138.7 (1h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66741
telemt_connections_bad_total 139
telemt_handshake_timeouts_total 2619
telemt_upstream_connect_attempt_total 2613
telemt_upstream_connect_success_total 2605
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 2613
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1355
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 161
telemt_me_reconnect_success_total 160
telemt_me_reader_eof_total 168
telemt_me_idle_close_by_peer_total 168
telemt_me_route_drop_no_conn_total 24709
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 237
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 151
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 100
telemt_pool_swap_total 1
telemt_pool_force_close_total 29
telemt_me_writer_removed_unexpected_total 168
telemt_me_writer_restored_same_endpoint_total 160
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 59252
telemt_user_connections_current{user="hello"} 483
telemt_user_octets_from_client{user="hello"} 593372956 (565.88 MB)
telemt_user_octets_to_client{user="hello"} 27369432572 (25.49 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 6138.4 (1h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121439
telemt_connections_bad_total 508
telemt_handshake_timeouts_total 10260
telemt_upstream_connect_attempt_total 3714
telemt_upstream_connect_success_total 3699
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 3711
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2083
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1611
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 882
telemt_me_reconnect_success_total 879
telemt_me_reader_eof_total 918
telemt_me_idle_close_by_peer_total 918
telemt_me_route_drop_no_conn_total 50773
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 219
telemt_desync_full_logged_total 58
telemt_desync_suppressed_total 161
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 89
telemt_desync_frames_bucket_total{bucket="gt_10"} 77
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 919
telemt_me_writer_restored_same_endpoint_total 874
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 107683
telemt_user_connections_current{user="hello"} 799
telemt_user_octets_from_client{user="hello"} 1184413928 (1.10 GB)
telemt_user_octets_to_client{user="hello"} 38641821300 (35.99 GB)
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 5454.7 (1h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61561
telemt_connections_bad_total 4921
telemt_handshake_timeouts_total 1395
telemt_upstream_connect_attempt_total 2664
telemt_upstream_connect_success_total 2664
telemt_upstream_connect_attempts_per_request{bucket="1"} 2664
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1553
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1111
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 372
telemt_me_reconnect_success_total 369
telemt_me_reader_eof_total 374
telemt_me_idle_close_by_peer_total 374
telemt_me_route_drop_no_conn_total 21748
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 81
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 21
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 1
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 374
telemt_me_writer_restored_same_endpoint_total 369
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 54126
telemt_user_connections_current{user="hello"} 422
telemt_user_octets_from_client{user="hello"} 624398992 (595.47 MB)
telemt_user_octets_to_client{user="hello"} 22817457416 (21.25 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 6138.7 (1h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119759
telemt_connections_bad_total 1107
telemt_handshake_timeouts_total 2050
telemt_upstream_connect_attempt_total 1548
telemt_upstream_connect_success_total 1545
telemt_upstream_connect_attempts_per_request{bucket="1"} 1545
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 749
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 24
telemt_me_reconnect_success_total 19
telemt_me_reader_eof_total 20
telemt_me_idle_close_by_peer_total 20
telemt_me_route_drop_no_conn_total 49672
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 172
telemt_desync_full_logged_total 58
telemt_desync_suppressed_total 114
telemt_desync_frames_bucket_total{bucket="1_2"} 70
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 2
telemt_pool_force_close_total 58
telemt_pool_stale_pick_total 101
telemt_me_writer_removed_unexpected_total 21
telemt_me_writer_restored_same_endpoint_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 107694
telemt_user_connections_current{user="hello"} 575
telemt_user_octets_from_client{user="hello"} 11511192004 (10.72 GB)
telemt_user_octets_to_client{user="hello"} 57013667516 (53.10 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 111
```