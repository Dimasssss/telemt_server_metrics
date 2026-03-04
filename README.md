# Server Metrics 2026-03-04 06:35:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 33875.3 (9h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 298735
telemt_connections_bad_total 3751
telemt_handshake_timeouts_total 5243
telemt_upstream_connect_attempt_total 22327
telemt_upstream_connect_success_total 22226
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 22226
telemt_upstream_connect_attempts_per_request{bucket="2"} 45
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12605
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9589
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 4646
telemt_me_reconnect_success_total 4621
telemt_me_reader_eof_total 4730
telemt_me_idle_close_by_peer_total 4730
telemt_me_route_drop_no_conn_total 112119
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 135
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 712
telemt_desync_full_logged_total 267
telemt_desync_suppressed_total 445
telemt_desync_frames_bucket_total{bucket="1_2"} 205
telemt_desync_frames_bucket_total{bucket="3_10"} 251
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 8
telemt_pool_force_close_total 300
telemt_me_writer_removed_unexpected_total 4730
telemt_me_writer_restored_same_endpoint_total 4601
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 277640
telemt_user_connections_current{user="hello"} 774
telemt_user_octets_from_client{user="hello"} 2888145680 (2.69 GB)
telemt_user_octets_to_client{user="hello"} 87094050312 (81.11 GB)
telemt_user_unique_ips_current{user="hello"} 110
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 33871.8 (9h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 147872
telemt_connections_bad_total 999
telemt_handshake_timeouts_total 22256
telemt_upstream_connect_attempt_total 72109
telemt_upstream_connect_success_total 71137
telemt_upstream_connect_fail_total 448
telemt_upstream_connect_attempts_per_request{bucket="1"} 71131
telemt_upstream_connect_attempts_per_request{bucket="2"} 454
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47999
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23116
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 448
telemt_me_keepalive_timeout_total 1149
telemt_me_reconnect_attempts_total 42749
telemt_me_reconnect_success_total 42677
telemt_me_reader_eof_total 43743
telemt_me_idle_close_by_peer_total 43742
telemt_me_route_drop_no_conn_total 47859
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 147
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 268
telemt_desync_full_logged_total 97
telemt_desync_suppressed_total 171
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 142
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 2
telemt_pool_force_close_total 138
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 43823
telemt_me_writer_restored_same_endpoint_total 42652
telemt_me_writer_removed_unexpected_minus_restored_total 1171
telemt_user_connections_total{user="hello"} 98307
telemt_user_connections_current{user="hello"} 372
telemt_user_octets_from_client{user="hello"} 962118536 (917.55 MB)
telemt_user_octets_to_client{user="hello"} 39248444332 (36.55 GB)
telemt_user_unique_ips_current{user="hello"} 38
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 33870.7 (9h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 290825
telemt_connections_bad_total 96442
telemt_handshake_timeouts_total 7533
telemt_upstream_connect_attempt_total 47507
telemt_upstream_connect_success_total 47216
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 47215
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27260
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19824
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 132
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 625
telemt_me_reconnect_attempts_total 20225
telemt_me_reconnect_success_total 20170
telemt_me_reader_eof_total 21302
telemt_me_idle_close_by_peer_total 21299
telemt_me_route_drop_no_conn_total 72808
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 144
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 442
telemt_desync_full_logged_total 165
telemt_desync_suppressed_total 277
telemt_desync_frames_bucket_total{bucket="1_2"} 118
telemt_desync_frames_bucket_total{bucket="3_10"} 164
telemt_desync_frames_bucket_total{bucket="gt_10"} 160
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 21310
telemt_me_writer_restored_same_endpoint_total 20149
telemt_me_writer_removed_unexpected_minus_restored_total 1161
telemt_user_connections_total{user="hello"} 178258
telemt_user_connections_current{user="hello"} 410
telemt_user_octets_from_client{user="hello"} 1416623348 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 49914495664 (46.49 GB)
telemt_user_unique_ips_current{user="hello"} 47
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 33869.6 (9h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 154759
telemt_connections_bad_total 12581
telemt_handshake_timeouts_total 4234
telemt_upstream_connect_attempt_total 26548
telemt_upstream_connect_success_total 26445
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 26445
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16355
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10089
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 291
telemt_me_reconnect_attempts_total 5955
telemt_me_reconnect_success_total 5945
telemt_me_reader_eof_total 6058
telemt_me_idle_close_by_peer_total 6058
telemt_me_route_drop_no_conn_total 45901
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 143
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 153
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 86
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 77
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 9
telemt_pool_force_close_total 213
telemt_me_writer_removed_unexpected_total 6058
telemt_me_writer_restored_same_endpoint_total 5924
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 129294
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 1297971132 (1.21 GB)
telemt_user_octets_to_client{user="hello"} 48649066016 (45.31 GB)
telemt_user_unique_ips_current{user="hello"} 28
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 33868.2 (9h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 300316
telemt_connections_bad_total 6395
telemt_handshake_timeouts_total 127669
telemt_upstream_connect_attempt_total 47301
telemt_upstream_connect_success_total 46970
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 46970
telemt_upstream_connect_attempts_per_request{bucket="2"} 155
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18876
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_keepalive_timeout_total 641
telemt_me_reconnect_attempts_total 21896
telemt_me_reconnect_success_total 21882
telemt_me_reader_eof_total 23081
telemt_me_idle_close_by_peer_total 23080
telemt_me_route_drop_no_conn_total 74067
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 144
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 208
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 141
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 111
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_pool_swap_total 4
telemt_pool_force_close_total 114
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 23094
telemt_me_writer_restored_same_endpoint_total 21857
telemt_me_writer_removed_unexpected_minus_restored_total 1237
telemt_user_connections_total{user="hello"} 160928
telemt_user_connections_current{user="hello"} 354
telemt_user_octets_from_client{user="hello"} 2244596200 (2.09 GB)
telemt_user_octets_to_client{user="hello"} 36890145876 (34.36 GB)
telemt_user_unique_ips_current{user="hello"} 33
```