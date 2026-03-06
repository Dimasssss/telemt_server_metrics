# Server Metrics 2026-03-06 14:53:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 16308.4 (4h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 484003
telemt_connections_bad_total 3036
telemt_handshake_timeouts_total 2631
telemt_upstream_connect_attempt_total 8421
telemt_upstream_connect_success_total 8369
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 8391
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4416
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3899
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 32
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 1831
telemt_me_reconnect_success_total 1821
telemt_me_reader_eof_total 1916
telemt_me_idle_close_by_peer_total 1916
telemt_me_route_drop_no_conn_total 172956
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 67
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 2614
telemt_desync_full_logged_total 640
telemt_desync_suppressed_total 1974
telemt_desync_frames_bucket_total{bucket="1_2"} 623
telemt_desync_frames_bucket_total{bucket="3_10"} 880
telemt_desync_frames_bucket_total{bucket="gt_10"} 1111
telemt_pool_swap_total 3
telemt_pool_force_close_total 177
telemt_me_writer_removed_unexpected_total 1918
telemt_me_writer_restored_same_endpoint_total 1815
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 414088
telemt_user_connections_current{user="hello"} 1128
telemt_user_octets_from_client{user="hello"} 11212108964 (10.44 GB)
telemt_user_octets_to_client{user="hello"} 167146443584 (155.67 GB)
telemt_user_unique_ips_current{user="hello"} 316
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 16308.2 (4h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 184971
telemt_connections_bad_total 856
telemt_handshake_timeouts_total 5914
telemt_upstream_connect_attempt_total 7215
telemt_upstream_connect_success_total 7195
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 7215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3381
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3814
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 635
telemt_me_reconnect_success_total 623
telemt_me_reader_eof_total 666
telemt_me_idle_close_by_peer_total 666
telemt_me_route_drop_no_conn_total 93113
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 70
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 679
telemt_desync_full_logged_total 215
telemt_desync_suppressed_total 464
telemt_desync_frames_bucket_total{bucket="1_2"} 112
telemt_desync_frames_bucket_total{bucket="3_10"} 259
telemt_desync_frames_bucket_total{bucket="gt_10"} 308
telemt_pool_swap_total 4
telemt_pool_force_close_total 140
telemt_me_writer_removed_unexpected_total 666
telemt_me_writer_restored_same_endpoint_total 623
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 169771
telemt_user_connections_current{user="hello"} 411
telemt_user_octets_from_client{user="hello"} 1923929840 (1.79 GB)
telemt_user_octets_to_client{user="hello"} 76122867220 (70.89 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 16308.1 (4h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 375653
telemt_connections_bad_total 5249
telemt_handshake_timeouts_total 36542
telemt_upstream_connect_attempt_total 13515
telemt_upstream_connect_success_total 13451
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 13504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7307
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6122
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 178
telemt_me_reconnect_attempts_total 4460
telemt_me_reconnect_success_total 4442
telemt_me_reader_eof_total 4708
telemt_me_idle_close_by_peer_total 4708
telemt_me_route_drop_no_conn_total 180620
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 67
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 675
telemt_desync_full_logged_total 205
telemt_desync_suppressed_total 470
telemt_desync_frames_bucket_total{bucket="1_2"} 154
telemt_desync_frames_bucket_total{bucket="3_10"} 274
telemt_desync_frames_bucket_total{bucket="gt_10"} 247
telemt_pool_swap_total 1
telemt_pool_force_close_total 84
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 4711
telemt_me_writer_restored_same_endpoint_total 4437
telemt_me_writer_removed_unexpected_minus_restored_total 274
telemt_user_connections_total{user="hello"} 321378
telemt_user_connections_current{user="hello"} 585
telemt_user_octets_from_client{user="hello"} 3436066956 (3.20 GB)
telemt_user_octets_to_client{user="hello"} 102495178052 (95.46 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 15624.3 (4h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 277517
telemt_connections_bad_total 55783
telemt_handshake_timeouts_total 9968
telemt_upstream_connect_attempt_total 8357
telemt_upstream_connect_success_total 8357
telemt_upstream_connect_attempts_per_request{bucket="1"} 8357
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5003
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3354
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 1524
telemt_me_reconnect_success_total 1511
telemt_me_reader_eof_total 1537
telemt_me_idle_close_by_peer_total 1537
telemt_me_route_drop_no_conn_total 95081
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 69
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 271
telemt_desync_full_logged_total 94
telemt_desync_suppressed_total 177
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 100
telemt_desync_frames_bucket_total{bucket="gt_10"} 104
telemt_pool_swap_total 3
telemt_pool_force_close_total 135
telemt_me_writer_removed_unexpected_total 1537
telemt_me_writer_restored_same_endpoint_total 1511
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 178176
telemt_user_connections_current{user="hello"} 477
telemt_user_octets_from_client{user="hello"} 2152162632 (2.00 GB)
telemt_user_octets_to_client{user="hello"} 67186427424 (62.57 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 16308.4 (4h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 292492
telemt_connections_bad_total 9204
telemt_handshake_timeouts_total 2644
telemt_upstream_connect_attempt_total 7957
telemt_upstream_connect_success_total 7946
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7947
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3667
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 132
telemt_me_reconnect_attempts_total 1664
telemt_me_reconnect_success_total 1651
telemt_me_reader_eof_total 1745
telemt_me_idle_close_by_peer_total 1744
telemt_me_route_drop_no_conn_total 154910
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 66
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 515
telemt_desync_full_logged_total 182
telemt_desync_suppressed_total 333
telemt_desync_frames_bucket_total{bucket="1_2"} 230
telemt_desync_frames_bucket_total{bucket="3_10"} 146
telemt_desync_frames_bucket_total{bucket="gt_10"} 139
telemt_pool_swap_total 4
telemt_pool_force_close_total 178
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 1749
telemt_me_writer_restored_same_endpoint_total 1650
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 267290
telemt_user_connections_current{user="hello"} 631
telemt_user_octets_from_client{user="hello"} 14464682924 (13.47 GB)
telemt_user_octets_to_client{user="hello"} 148197077488 (138.02 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 110
```