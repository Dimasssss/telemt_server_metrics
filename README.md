# Server Metrics 2026-03-04 06:24:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 33261.0 (9h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 285852
telemt_connections_bad_total 3095
telemt_handshake_timeouts_total 5110
telemt_upstream_connect_attempt_total 22187
telemt_upstream_connect_success_total 22085
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 22085
telemt_upstream_connect_attempts_per_request{bucket="2"} 45
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9521
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 235
telemt_me_reconnect_attempts_total 4644
telemt_me_reconnect_success_total 4619
telemt_me_reader_eof_total 4728
telemt_me_idle_close_by_peer_total 4728
telemt_me_route_drop_no_conn_total 108147
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 134
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 694
telemt_desync_full_logged_total 259
telemt_desync_suppressed_total 435
telemt_desync_frames_bucket_total{bucket="1_2"} 199
telemt_desync_frames_bucket_total{bucket="3_10"} 245
telemt_desync_frames_bucket_total{bucket="gt_10"} 250
telemt_pool_swap_total 7
telemt_pool_force_close_total 253
telemt_me_writer_removed_unexpected_total 4728
telemt_me_writer_restored_same_endpoint_total 4599
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 266434
telemt_user_connections_current{user="hello"} 788
telemt_user_octets_from_client{user="hello"} 2827985040 (2.63 GB)
telemt_user_octets_to_client{user="hello"} 84164519988 (78.38 GB)
telemt_user_unique_ips_current{user="hello"} 86
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 33257.5 (9h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143811
telemt_connections_bad_total 862
telemt_handshake_timeouts_total 22166
telemt_upstream_connect_attempt_total 71635
telemt_upstream_connect_success_total 70762
telemt_upstream_connect_fail_total 420
telemt_upstream_connect_attempts_per_request{bucket="1"} 70756
telemt_upstream_connect_attempts_per_request{bucket="2"} 426
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47736
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23006
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 420
telemt_me_keepalive_timeout_total 1044
telemt_me_reconnect_attempts_total 42649
telemt_me_reconnect_success_total 42617
telemt_me_reader_eof_total 43688
telemt_me_idle_close_by_peer_total 43687
telemt_me_route_drop_no_conn_total 46056
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 142
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 255
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 159
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 138
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 2
telemt_pool_force_close_total 138
telemt_pool_stale_pick_total 44
telemt_me_writer_removed_unexpected_total 43749
telemt_me_writer_restored_same_endpoint_total 42596
telemt_me_writer_removed_unexpected_minus_restored_total 1153
telemt_user_connections_total{user="hello"} 94561
telemt_user_connections_current{user="hello"} 288
telemt_user_octets_from_client{user="hello"} 932056336 (888.88 MB)
telemt_user_octets_to_client{user="hello"} 38407068160 (35.77 GB)
telemt_user_unique_ips_current{user="hello"} 25
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 33256.3 (9h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 282307
telemt_connections_bad_total 94853
telemt_handshake_timeouts_total 6890
telemt_upstream_connect_attempt_total 46111
telemt_upstream_connect_success_total 45827
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 45827
telemt_upstream_connect_attempts_per_request{bucket="2"} 133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26508
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 131
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 604
telemt_me_reconnect_attempts_total 19428
telemt_me_reconnect_success_total 19375
telemt_me_reader_eof_total 20464
telemt_me_idle_close_by_peer_total 20461
telemt_me_route_drop_no_conn_total 69599
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 141
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 428
telemt_desync_full_logged_total 160
telemt_desync_suppressed_total 268
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 163
telemt_desync_frames_bucket_total{bucket="gt_10"} 155
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 20472
telemt_me_writer_restored_same_endpoint_total 19354
telemt_me_writer_removed_unexpected_minus_restored_total 1118
telemt_user_connections_total{user="hello"} 172206
telemt_user_connections_current{user="hello"} 360
telemt_user_octets_from_client{user="hello"} 1342150500 (1.25 GB)
telemt_user_octets_to_client{user="hello"} 45934722040 (42.78 GB)
telemt_user_unique_ips_current{user="hello"} 49
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 33255.3 (9h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148259
telemt_connections_bad_total 12030
telemt_handshake_timeouts_total 3653
telemt_upstream_connect_attempt_total 26226
telemt_upstream_connect_success_total 26133
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 26133
telemt_upstream_connect_attempts_per_request{bucket="2"} 46
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9982
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 285
telemt_me_reconnect_attempts_total 5940
telemt_me_reconnect_success_total 5930
telemt_me_reader_eof_total 6043
telemt_me_idle_close_by_peer_total 6043
telemt_me_route_drop_no_conn_total 44444
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 139
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 145
telemt_desync_full_logged_total 64
telemt_desync_suppressed_total 81
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 9
telemt_pool_force_close_total 213
telemt_me_writer_removed_unexpected_total 6043
telemt_me_writer_restored_same_endpoint_total 5909
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 124691
telemt_user_connections_current{user="hello"} 310
telemt_user_octets_from_client{user="hello"} 1212313688 (1.13 GB)
telemt_user_octets_to_client{user="hello"} 45943364288 (42.79 GB)
telemt_user_unique_ips_current{user="hello"} 28
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 33253.9 (9h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 293789
telemt_connections_bad_total 6394
telemt_handshake_timeouts_total 127245
telemt_upstream_connect_attempt_total 46610
telemt_upstream_connect_success_total 46284
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 46284
telemt_upstream_connect_attempts_per_request{bucket="2"} 153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27566
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18599
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 117
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_keepalive_timeout_total 633
telemt_me_reconnect_attempts_total 21728
telemt_me_reconnect_success_total 21715
telemt_me_reader_eof_total 22908
telemt_me_idle_close_by_peer_total 22907
telemt_me_route_drop_no_conn_total 70912
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 141
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 202
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 137
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 63
telemt_pool_swap_total 4
telemt_pool_force_close_total 114
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 22921
telemt_me_writer_restored_same_endpoint_total 21690
telemt_me_writer_removed_unexpected_minus_restored_total 1231
telemt_user_connections_total{user="hello"} 155028
telemt_user_connections_current{user="hello"} 309
telemt_user_octets_from_client{user="hello"} 2214711968 (2.06 GB)
telemt_user_octets_to_client{user="hello"} 36064304480 (33.59 GB)
telemt_user_unique_ips_current{user="hello"} 39
```