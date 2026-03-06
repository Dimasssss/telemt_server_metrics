# Server Metrics 2026-03-06 17:12:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 24653.7 (6h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 737107
telemt_connections_bad_total 12135
telemt_handshake_timeouts_total 3232
telemt_upstream_connect_attempt_total 12507
telemt_upstream_connect_success_total 12431
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 12463
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5672
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 45
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 164
telemt_me_reconnect_attempts_total 2416
telemt_me_reconnect_success_total 2398
telemt_me_reader_eof_total 2510
telemt_me_idle_close_by_peer_total 2510
telemt_me_route_drop_no_conn_total 313485
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 100
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 3773
telemt_desync_full_logged_total 915
telemt_desync_suppressed_total 2858
telemt_desync_frames_bucket_total{bucket="1_2"} 892
telemt_desync_frames_bucket_total{bucket="3_10"} 1323
telemt_desync_frames_bucket_total{bucket="gt_10"} 1558
telemt_pool_swap_total 4
telemt_pool_force_close_total 234
telemt_me_writer_removed_unexpected_total 2513
telemt_me_writer_restored_same_endpoint_total 2392
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 631573
telemt_user_connections_current{user="hello"} 999
telemt_user_octets_from_client{user="hello"} 13478055836 (12.55 GB)
telemt_user_octets_to_client{user="hello"} 229426035452 (213.67 GB)
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 24653.6 (6h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 274637
telemt_connections_bad_total 974
telemt_handshake_timeouts_total 8189
telemt_upstream_connect_attempt_total 11257
telemt_upstream_connect_success_total 11225
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 11257
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5369
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5855
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 147
telemt_me_reconnect_attempts_total 964
telemt_me_reconnect_success_total 942
telemt_me_reader_eof_total 994
telemt_me_idle_close_by_peer_total 994
telemt_me_route_drop_no_conn_total 151629
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 101
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 870
telemt_desync_full_logged_total 275
telemt_desync_suppressed_total 595
telemt_desync_frames_bucket_total{bucket="1_2"} 161
telemt_desync_frames_bucket_total{bucket="3_10"} 312
telemt_desync_frames_bucket_total{bucket="gt_10"} 397
telemt_pool_swap_total 7
telemt_pool_force_close_total 282
telemt_me_writer_removed_unexpected_total 995
telemt_me_writer_restored_same_endpoint_total 942
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 252706
telemt_user_connections_current{user="hello"} 445
telemt_user_octets_from_client{user="hello"} 3003297392 (2.80 GB)
telemt_user_octets_to_client{user="hello"} 102105795088 (95.09 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 24653.4 (6h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 540178
telemt_connections_bad_total 5499
telemt_handshake_timeouts_total 52310
telemt_upstream_connect_attempt_total 21734
telemt_upstream_connect_success_total 21627
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 21704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11909
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9667
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 321
telemt_me_reconnect_attempts_total 7542
telemt_me_reconnect_success_total 7514
telemt_me_reader_eof_total 7980
telemt_me_idle_close_by_peer_total 7980
telemt_me_route_drop_no_conn_total 284974
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 102
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1289
telemt_desync_full_logged_total 383
telemt_desync_suppressed_total 906
telemt_desync_frames_bucket_total{bucket="1_2"} 291
telemt_desync_frames_bucket_total{bucket="3_10"} 483
telemt_desync_frames_bucket_total{bucket="gt_10"} 515
telemt_pool_swap_total 2
telemt_pool_force_close_total 169
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 7995
telemt_me_writer_restored_same_endpoint_total 7507
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 486
telemt_user_connections_total{user="hello"} 464375
telemt_user_connections_current{user="hello"} 551
telemt_user_octets_from_client{user="hello"} 6862514832 (6.39 GB)
telemt_user_octets_to_client{user="hello"} 143261811064 (133.42 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 23969.8 (6h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 518850
telemt_connections_bad_total 178008
telemt_handshake_timeouts_total 13071
telemt_upstream_connect_attempt_total 15685
telemt_upstream_connect_success_total 15683
telemt_upstream_connect_attempts_per_request{bucket="1"} 15683
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8923
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6760
telemt_me_keepalive_timeout_total 210
telemt_me_reconnect_attempts_total 4131
telemt_me_reconnect_success_total 4109
telemt_me_reader_eof_total 4294
telemt_me_idle_close_by_peer_total 4294
telemt_me_route_drop_no_conn_total 165626
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 103
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 360
telemt_desync_full_logged_total 137
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 91
telemt_desync_frames_bucket_total{bucket="3_10"} 123
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 4
telemt_pool_force_close_total 192
telemt_me_writer_removed_unexpected_total 4301
telemt_me_writer_restored_same_endpoint_total 4108
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 192
telemt_user_connections_total{user="hello"} 290717
telemt_user_connections_current{user="hello"} 525
telemt_user_octets_from_client{user="hello"} 4898755176 (4.56 GB)
telemt_user_octets_to_client{user="hello"} 100474989788 (93.57 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 24653.9 (6h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 444568
telemt_connections_bad_total 11134
telemt_handshake_timeouts_total 4068
telemt_upstream_connect_attempt_total 10755
telemt_upstream_connect_success_total 10738
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10739
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5814
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4859
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 178
telemt_me_reconnect_attempts_total 1787
telemt_me_reconnect_success_total 1767
telemt_me_reader_eof_total 1867
telemt_me_idle_close_by_peer_total 1866
telemt_me_route_drop_no_conn_total 217342
telemt_me_route_drop_channel_closed_total 6
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 96
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 859
telemt_desync_full_logged_total 306
telemt_desync_suppressed_total 553
telemt_desync_frames_bucket_total{bucket="1_2"} 384
telemt_desync_frames_bucket_total{bucket="3_10"} 249
telemt_desync_frames_bucket_total{bucket="gt_10"} 226
telemt_pool_swap_total 8
telemt_pool_force_close_total 297
telemt_pool_stale_pick_total 200
telemt_me_writer_removed_unexpected_total 1871
telemt_me_writer_restored_same_endpoint_total 1764
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 408647
telemt_user_connections_current{user="hello"} 532
telemt_user_octets_from_client{user="hello"} 20058011228 (18.68 GB)
telemt_user_octets_to_client{user="hello"} 204679635188 (190.62 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 91
```