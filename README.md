# Server Metrics 2026-03-04 02:44:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 20040.8 (5h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127343
telemt_connections_bad_total 1379
telemt_handshake_timeouts_total 1048
telemt_upstream_connect_attempt_total 16164
telemt_upstream_connect_success_total 16093
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 16093
telemt_upstream_connect_attempts_per_request{bucket="2"} 31
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9097
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6975
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 164
telemt_me_reconnect_attempts_total 4139
telemt_me_reconnect_success_total 4131
telemt_me_reader_eof_total 4226
telemt_me_idle_close_by_peer_total 4226
telemt_me_route_drop_no_conn_total 45427
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 233
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 155
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 73
telemt_desync_frames_bucket_total{bucket="gt_10"} 91
telemt_pool_swap_total 3
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 4226
telemt_me_writer_restored_same_endpoint_total 4111
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 122074
telemt_user_connections_current{user="hello"} 327
telemt_user_octets_from_client{user="hello"} 1048212752 (999.65 MB)
telemt_user_octets_to_client{user="hello"} 36359009736 (33.86 GB)
telemt_user_unique_ips_current{user="hello"} 47
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 20037.4 (5h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59793
telemt_connections_bad_total 277
telemt_handshake_timeouts_total 15517
telemt_upstream_connect_attempt_total 48011
telemt_upstream_connect_success_total 47486
telemt_upstream_connect_fail_total 246
telemt_upstream_connect_attempts_per_request{bucket="1"} 47480
telemt_upstream_connect_attempts_per_request{bucket="2"} 252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32376
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15091
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 246
telemt_me_keepalive_timeout_total 834
telemt_me_reconnect_attempts_total 29501
telemt_me_reconnect_success_total 29480
telemt_me_reader_eof_total 30247
telemt_me_idle_close_by_peer_total 30246
telemt_me_route_drop_no_conn_total 19804
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 89
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 90
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 52
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_me_writer_removed_unexpected_total 30308
telemt_me_writer_restored_same_endpoint_total 29460
telemt_me_writer_removed_unexpected_minus_restored_total 848
telemt_user_connections_total{user="hello"} 43295
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 338108824 (322.45 MB)
telemt_user_octets_to_client{user="hello"} 23806808748 (22.17 GB)
telemt_user_unique_ips_current{user="hello"} 31
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 20036.3 (5h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141262
telemt_connections_bad_total 50827
telemt_handshake_timeouts_total 3273
telemt_upstream_connect_attempt_total 23976
telemt_upstream_connect_success_total 23815
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 23815
telemt_upstream_connect_attempts_per_request{bucket="2"} 74
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14044
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9694
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 302
telemt_me_reconnect_attempts_total 8388
telemt_me_reconnect_success_total 8372
telemt_me_reader_eof_total 8720
telemt_me_idle_close_by_peer_total 8718
telemt_me_route_drop_no_conn_total 27304
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 87
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 289
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 189
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 106
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 2
telemt_pool_force_close_total 63
telemt_me_writer_removed_unexpected_total 8722
telemt_me_writer_restored_same_endpoint_total 8351
telemt_me_writer_removed_unexpected_minus_restored_total 371
telemt_user_connections_total{user="hello"} 83820
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 509472832 (485.87 MB)
telemt_user_octets_to_client{user="hello"} 20466521192 (19.06 GB)
telemt_user_unique_ips_current{user="hello"} 20
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 20035.1 (5h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63473
telemt_connections_bad_total 192
telemt_handshake_timeouts_total 650
telemt_upstream_connect_attempt_total 12647
telemt_upstream_connect_success_total 12582
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 12582
telemt_upstream_connect_attempts_per_request{bucket="2"} 32
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7823
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4758
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 128
telemt_me_reconnect_attempts_total 1713
telemt_me_reconnect_success_total 1718
telemt_me_reader_eof_total 1725
telemt_me_idle_close_by_peer_total 1725
telemt_me_route_drop_no_conn_total 21821
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 86
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 23
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 13
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 6
telemt_pool_force_close_total 139
telemt_me_writer_removed_unexpected_total 1725
telemt_me_writer_restored_same_endpoint_total 1698
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 61510
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 503745504 (480.41 MB)
telemt_user_octets_to_client{user="hello"} 20995656056 (19.55 GB)
telemt_user_unique_ips_current{user="hello"} 25
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 20033.9 (5h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152845
telemt_connections_bad_total 85
telemt_handshake_timeouts_total 68874
telemt_upstream_connect_attempt_total 29267
telemt_upstream_connect_success_total 29084
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 29084
telemt_upstream_connect_attempts_per_request{bucket="2"} 87
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16849
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12170
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_timeout_total 392
telemt_me_reconnect_attempts_total 14610
telemt_me_reconnect_success_total 14607
telemt_me_reader_eof_total 15521
telemt_me_idle_close_by_peer_total 15520
telemt_me_route_drop_no_conn_total 42229
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 86
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 109
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 83
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 2
telemt_pool_force_close_total 59
telemt_pool_stale_pick_total 2235
telemt_me_writer_removed_unexpected_total 15526
telemt_me_writer_restored_same_endpoint_total 14583
telemt_me_writer_removed_unexpected_minus_restored_total 943
telemt_user_connections_total{user="hello"} 80955
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 462883668 (441.44 MB)
telemt_user_octets_to_client{user="hello"} 18177546028 (16.93 GB)
telemt_user_unique_ips_current{user="hello"} 20
```