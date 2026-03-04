# Server Metrics 2026-03-04 04:32:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 26489.0 (7h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179042
telemt_connections_bad_total 1625
telemt_handshake_timeouts_total 3134
telemt_upstream_connect_attempt_total 19261
telemt_upstream_connect_success_total 19176
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 19176
telemt_upstream_connect_attempts_per_request{bucket="2"} 38
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10845
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8306
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 206
telemt_me_reconnect_attempts_total 4406
telemt_me_reconnect_success_total 4390
telemt_me_reader_eof_total 4495
telemt_me_idle_close_by_peer_total 4495
telemt_me_route_drop_no_conn_total 59349
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 109
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 477
telemt_desync_full_logged_total 167
telemt_desync_suppressed_total 310
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 167
telemt_desync_frames_bucket_total{bucket="gt_10"} 183
telemt_pool_swap_total 5
telemt_pool_force_close_total 168
telemt_me_writer_removed_unexpected_total 4495
telemt_me_writer_restored_same_endpoint_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 169995
telemt_user_connections_current{user="hello"} 599
telemt_user_octets_from_client{user="hello"} 1794917436 (1.67 GB)
telemt_user_octets_to_client{user="hello"} 54777093304 (51.02 GB)
telemt_user_unique_ips_current{user="hello"} 58
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 26485.4 (7h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83741
telemt_connections_bad_total 350
telemt_handshake_timeouts_total 20708
telemt_upstream_connect_attempt_total 62199
telemt_upstream_connect_success_total 61541
telemt_upstream_connect_fail_total 313
telemt_upstream_connect_attempts_per_request{bucket="1"} 61535
telemt_upstream_connect_attempts_per_request{bucket="2"} 319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41941
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19580
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 313
telemt_me_keepalive_timeout_total 958
telemt_me_reconnect_attempts_total 38638
telemt_me_reconnect_success_total 38611
telemt_me_reader_eof_total 39589
telemt_me_idle_close_by_peer_total 39588
telemt_me_route_drop_no_conn_total 26581
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 116
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 194
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 114
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 102
telemt_desync_frames_bucket_total{bucket="gt_10"} 50
telemt_pool_swap_total 1
telemt_pool_force_close_total 75
telemt_me_writer_removed_unexpected_total 39650
telemt_me_writer_restored_same_endpoint_total 38590
telemt_me_writer_removed_unexpected_minus_restored_total 1060
telemt_user_connections_total{user="hello"} 61397
telemt_user_connections_current{user="hello"} 287
telemt_user_octets_from_client{user="hello"} 582787212 (555.79 MB)
telemt_user_octets_to_client{user="hello"} 28363011576 (26.42 GB)
telemt_user_unique_ips_current{user="hello"} 32
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 26484.2 (7h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 191020
telemt_connections_bad_total 69508
telemt_handshake_timeouts_total 4263
telemt_upstream_connect_attempt_total 34642
telemt_upstream_connect_success_total 34413
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 34413
telemt_upstream_connect_attempts_per_request{bucket="2"} 106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14070
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 459
telemt_me_reconnect_attempts_total 14009
telemt_me_reconnect_success_total 13973
telemt_me_reader_eof_total 14709
telemt_me_idle_close_by_peer_total 14706
telemt_me_route_drop_no_conn_total 38296
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 114
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 309
telemt_desync_full_logged_total 109
telemt_desync_suppressed_total 200
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 111
telemt_desync_frames_bucket_total{bucket="gt_10"} 130
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 14717
telemt_me_writer_restored_same_endpoint_total 13952
telemt_me_writer_removed_unexpected_minus_restored_total 765
telemt_user_connections_total{user="hello"} 113432
telemt_user_connections_current{user="hello"} 303
telemt_user_octets_from_client{user="hello"} 721999896 (688.55 MB)
telemt_user_octets_to_client{user="hello"} 29119161032 (27.12 GB)
telemt_user_unique_ips_current{user="hello"} 33
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 26483.2 (7h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95137
telemt_connections_bad_total 4611
telemt_handshake_timeouts_total 1023
telemt_upstream_connect_attempt_total 17962
telemt_upstream_connect_success_total 17883
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 17883
telemt_upstream_connect_attempts_per_request{bucket="2"} 39
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6810
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 186
telemt_me_reconnect_attempts_total 2828
telemt_me_reconnect_success_total 2828
telemt_me_reader_eof_total 2850
telemt_me_idle_close_by_peer_total 2850
telemt_me_route_drop_no_conn_total 30849
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 111
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 109
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 64
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 8
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 2850
telemt_me_writer_restored_same_endpoint_total 2807
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 85457
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 718703588 (685.41 MB)
telemt_user_octets_to_client{user="hello"} 28656417264 (26.69 GB)
telemt_user_unique_ips_current{user="hello"} 31
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 26481.8 (7h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 209715
telemt_connections_bad_total 4079
telemt_handshake_timeouts_total 95932
telemt_upstream_connect_attempt_total 39136
telemt_upstream_connect_success_total 38863
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 38863
telemt_upstream_connect_attempts_per_request{bucket="2"} 127
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22838
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15923
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_timeout_total 546
telemt_me_reconnect_attempts_total 19185
telemt_me_reconnect_success_total 19177
telemt_me_reader_eof_total 20295
telemt_me_idle_close_by_peer_total 20294
telemt_me_route_drop_no_conn_total 50169
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 114
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 150
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 108
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 3
telemt_pool_force_close_total 85
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 20307
telemt_me_writer_restored_same_endpoint_total 19153
telemt_me_writer_removed_unexpected_minus_restored_total 1154
telemt_user_connections_total{user="hello"} 105981
telemt_user_connections_current{user="hello"} 232
telemt_user_octets_from_client{user="hello"} 688122368 (656.24 MB)
telemt_user_octets_to_client{user="hello"} 24172315192 (22.51 GB)
telemt_user_unique_ips_current{user="hello"} 30
```