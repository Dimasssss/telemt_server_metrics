# Server Metrics 2026-03-06 15:35:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 18804.8 (5h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 559811
telemt_connections_bad_total 5467
telemt_handshake_timeouts_total 2859
telemt_upstream_connect_attempt_total 9620
telemt_upstream_connect_success_total 9562
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 9586
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5059
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4442
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 126
telemt_me_reconnect_attempts_total 1949
telemt_me_reconnect_success_total 1937
telemt_me_reader_eof_total 2034
telemt_me_idle_close_by_peer_total 2034
telemt_me_route_drop_no_conn_total 200197
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 75
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 2989
telemt_desync_full_logged_total 731
telemt_desync_suppressed_total 2258
telemt_desync_frames_bucket_total{bucket="1_2"} 717
telemt_desync_frames_bucket_total{bucket="3_10"} 1010
telemt_desync_frames_bucket_total{bucket="gt_10"} 1262
telemt_pool_swap_total 3
telemt_pool_force_close_total 177
telemt_me_writer_removed_unexpected_total 2036
telemt_me_writer_restored_same_endpoint_total 1931
telemt_me_writer_removed_unexpected_minus_restored_total 105
telemt_user_connections_total{user="hello"} 476406
telemt_user_connections_current{user="hello"} 1050
telemt_user_octets_from_client{user="hello"} 11855123824 (11.04 GB)
telemt_user_octets_to_client{user="hello"} 186821924604 (173.99 GB)
telemt_user_unique_ips_current{user="hello"} 297
telemt_user_unique_ips_recent_window{user="hello"} 185
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 18804.7 (5h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 213023
telemt_connections_bad_total 861
telemt_handshake_timeouts_total 6613
telemt_upstream_connect_attempt_total 8896
telemt_upstream_connect_success_total 8876
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 8896
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4243
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4632
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 113
telemt_me_reconnect_attempts_total 914
telemt_me_reconnect_success_total 899
telemt_me_reader_eof_total 949
telemt_me_idle_close_by_peer_total 949
telemt_me_route_drop_no_conn_total 104946
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 746
telemt_desync_full_logged_total 240
telemt_desync_suppressed_total 506
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 280
telemt_desync_frames_bucket_total{bucket="gt_10"} 339
telemt_pool_swap_total 5
telemt_pool_force_close_total 196
telemt_me_writer_removed_unexpected_total 949
telemt_me_writer_restored_same_endpoint_total 899
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 196368
telemt_user_connections_current{user="hello"} 510
telemt_user_octets_from_client{user="hello"} 2190991300 (2.04 GB)
telemt_user_octets_to_client{user="hello"} 82978477328 (77.28 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 18804.6 (5h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 423856
telemt_connections_bad_total 5297
telemt_handshake_timeouts_total 38328
telemt_upstream_connect_attempt_total 15654
telemt_upstream_connect_success_total 15583
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 15642
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7007
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 212
telemt_me_reconnect_attempts_total 5334
telemt_me_reconnect_success_total 5313
telemt_me_reader_eof_total 5628
telemt_me_idle_close_by_peer_total 5628
telemt_me_route_drop_no_conn_total 200872
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 75
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 811
telemt_desync_full_logged_total 247
telemt_desync_suppressed_total 564
telemt_desync_frames_bucket_total{bucket="1_2"} 193
telemt_desync_frames_bucket_total{bucket="3_10"} 319
telemt_desync_frames_bucket_total{bucket="gt_10"} 299
telemt_pool_swap_total 2
telemt_pool_force_close_total 169
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 5632
telemt_me_writer_restored_same_endpoint_total 5308
telemt_me_writer_removed_unexpected_minus_restored_total 324
telemt_user_connections_total{user="hello"} 366775
telemt_user_connections_current{user="hello"} 671
telemt_user_octets_from_client{user="hello"} 5582766344 (5.20 GB)
telemt_user_octets_to_client{user="hello"} 117301998088 (109.25 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 18120.8 (5h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 331692
telemt_connections_bad_total 76620
telemt_handshake_timeouts_total 10343
telemt_upstream_connect_attempt_total 9718
telemt_upstream_connect_success_total 9717
telemt_upstream_connect_attempts_per_request{bucket="1"} 9717
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5844
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3873
telemt_me_keepalive_timeout_total 115
telemt_me_reconnect_attempts_total 1931
telemt_me_reconnect_success_total 1916
telemt_me_reader_eof_total 1951
telemt_me_idle_close_by_peer_total 1951
telemt_me_route_drop_no_conn_total 107922
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 79
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 284
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 100
telemt_desync_frames_bucket_total{bucket="gt_10"} 105
telemt_pool_swap_total 4
telemt_pool_force_close_total 192
telemt_me_writer_removed_unexpected_total 1951
telemt_me_writer_restored_same_endpoint_total 1916
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 210322
telemt_user_connections_current{user="hello"} 622
telemt_user_octets_from_client{user="hello"} 2482165524 (2.31 GB)
telemt_user_octets_to_client{user="hello"} 77356823140 (72.04 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 18804.9 (5h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 333125
telemt_connections_bad_total 10807
telemt_handshake_timeouts_total 2753
telemt_upstream_connect_attempt_total 9192
telemt_upstream_connect_success_total 9180
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9181
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4158
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 147
telemt_me_reconnect_attempts_total 1747
telemt_me_reconnect_success_total 1731
telemt_me_reader_eof_total 1827
telemt_me_idle_close_by_peer_total 1826
telemt_me_route_drop_no_conn_total 171655
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 74
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 609
telemt_desync_full_logged_total 214
telemt_desync_suppressed_total 395
telemt_desync_frames_bucket_total{bucket="1_2"} 278
telemt_desync_frames_bucket_total{bucket="3_10"} 179
telemt_desync_frames_bucket_total{bucket="gt_10"} 152
telemt_pool_swap_total 4
telemt_pool_force_close_total 178
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 1831
telemt_me_writer_restored_same_endpoint_total 1730
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 305365
telemt_user_connections_current{user="hello"} 548
telemt_user_octets_from_client{user="hello"} 14891673792 (13.87 GB)
telemt_user_octets_to_client{user="hello"} 164594601196 (153.29 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 105
```