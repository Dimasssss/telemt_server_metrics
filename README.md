# Server Metrics 2026-03-04 06:45:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 34489.5 (9h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 320833
telemt_connections_bad_total 4283
telemt_handshake_timeouts_total 5682
telemt_upstream_connect_attempt_total 22495
telemt_upstream_connect_success_total 22388
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 22388
telemt_upstream_connect_attempts_per_request{bucket="2"} 48
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12694
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9662
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 4650
telemt_me_reconnect_success_total 4625
telemt_me_reader_eof_total 4734
telemt_me_idle_close_by_peer_total 4734
telemt_me_route_drop_no_conn_total 115356
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 139
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 733
telemt_desync_full_logged_total 274
telemt_desync_suppressed_total 459
telemt_desync_frames_bucket_total{bucket="1_2"} 211
telemt_desync_frames_bucket_total{bucket="3_10"} 257
telemt_desync_frames_bucket_total{bucket="gt_10"} 265
telemt_pool_swap_total 8
telemt_pool_force_close_total 300
telemt_me_writer_removed_unexpected_total 4734
telemt_me_writer_restored_same_endpoint_total 4605
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 287791
telemt_user_connections_current{user="hello"} 745
telemt_user_octets_from_client{user="hello"} 3042413796 (2.83 GB)
telemt_user_octets_to_client{user="hello"} 89454970048 (83.31 GB)
telemt_user_unique_ips_current{user="hello"} 92
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 34486.1 (9h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152431
telemt_connections_bad_total 1144
telemt_handshake_timeouts_total 22418
telemt_upstream_connect_attempt_total 72523
telemt_upstream_connect_success_total 71518
telemt_upstream_connect_fail_total 464
telemt_upstream_connect_attempts_per_request{bucket="1"} 71512
telemt_upstream_connect_attempts_per_request{bucket="2"} 470
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48270
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23226
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 464
telemt_me_keepalive_timeout_total 1151
telemt_me_reconnect_attempts_total 42857
telemt_me_reconnect_success_total 42784
telemt_me_reader_eof_total 43851
telemt_me_idle_close_by_peer_total 43850
telemt_me_route_drop_no_conn_total 50809
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 149
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 278
telemt_desync_full_logged_total 98
telemt_desync_suppressed_total 180
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 148
telemt_desync_frames_bucket_total{bucket="gt_10"} 63
telemt_pool_swap_total 2
telemt_pool_force_close_total 138
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 43931
telemt_me_writer_restored_same_endpoint_total 42759
telemt_me_writer_removed_unexpected_minus_restored_total 1172
telemt_user_connections_total{user="hello"} 102478
telemt_user_connections_current{user="hello"} 363
telemt_user_octets_from_client{user="hello"} 985900932 (940.23 MB)
telemt_user_octets_to_client{user="hello"} 40878133564 (38.07 GB)
telemt_user_unique_ips_current{user="hello"} 35
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 34484.9 (9h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 299539
telemt_connections_bad_total 98038
telemt_handshake_timeouts_total 8256
telemt_upstream_connect_attempt_total 48759
telemt_upstream_connect_success_total 48453
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 48452
telemt_upstream_connect_attempts_per_request{bucket="2"} 144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27939
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20378
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 643
telemt_me_reconnect_attempts_total 20888
telemt_me_reconnect_success_total 20832
telemt_me_reader_eof_total 21990
telemt_me_idle_close_by_peer_total 21987
telemt_me_route_drop_no_conn_total 76686
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 147
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 458
telemt_desync_full_logged_total 172
telemt_desync_suppressed_total 286
telemt_desync_frames_bucket_total{bucket="1_2"} 121
telemt_desync_frames_bucket_total{bucket="3_10"} 168
telemt_desync_frames_bucket_total{bucket="gt_10"} 169
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 21998
telemt_me_writer_restored_same_endpoint_total 20811
telemt_me_writer_removed_unexpected_minus_restored_total 1187
telemt_user_connections_total{user="hello"} 184635
telemt_user_connections_current{user="hello"} 413
telemt_user_octets_from_client{user="hello"} 1509375272 (1.41 GB)
telemt_user_octets_to_client{user="hello"} 56470490548 (52.59 GB)
telemt_user_unique_ips_current{user="hello"} 45
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 34483.9 (9h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 163155
telemt_connections_bad_total 13139
telemt_handshake_timeouts_total 4852
telemt_upstream_connect_attempt_total 26875
telemt_upstream_connect_success_total 26772
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 26772
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16569
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10202
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 295
telemt_me_reconnect_attempts_total 5984
telemt_me_reconnect_success_total 5973
telemt_me_reader_eof_total 6086
telemt_me_idle_close_by_peer_total 6086
telemt_me_route_drop_no_conn_total 47426
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 145
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 166
telemt_desync_full_logged_total 69
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 10
telemt_pool_force_close_total 232
telemt_me_writer_removed_unexpected_total 6086
telemt_me_writer_restored_same_endpoint_total 5952
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 133067
telemt_user_connections_current{user="hello"} 255
telemt_user_octets_from_client{user="hello"} 1320612240 (1.23 GB)
telemt_user_octets_to_client{user="hello"} 49499853488 (46.10 GB)
telemt_user_unique_ips_current{user="hello"} 51
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 34482.5 (9h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 307201
telemt_connections_bad_total 6395
telemt_handshake_timeouts_total 128122
telemt_upstream_connect_attempt_total 48047
telemt_upstream_connect_success_total 47714
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 47714
telemt_upstream_connect_attempts_per_request{bucket="2"} 156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28432
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19159
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_timeout_total 648
telemt_me_reconnect_attempts_total 22114
telemt_me_reconnect_success_total 22100
telemt_me_reader_eof_total 23303
telemt_me_idle_close_by_peer_total 23302
telemt_me_route_drop_no_conn_total 77439
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 146
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 219
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 148
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 114
telemt_desync_frames_bucket_total{bucket="gt_10"} 71
telemt_pool_swap_total 4
telemt_pool_force_close_total 114
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 23316
telemt_me_writer_restored_same_endpoint_total 22075
telemt_me_writer_removed_unexpected_minus_restored_total 1241
telemt_user_connections_total{user="hello"} 167135
telemt_user_connections_current{user="hello"} 403
telemt_user_octets_from_client{user="hello"} 2290694020 (2.13 GB)
telemt_user_octets_to_client{user="hello"} 37634045836 (35.05 GB)
telemt_user_unique_ips_current{user="hello"} 41
```