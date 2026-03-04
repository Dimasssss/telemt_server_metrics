# Server Metrics 2026-03-04 06:40:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 34182.6 (9h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 309453
telemt_connections_bad_total 4019
telemt_handshake_timeouts_total 5453
telemt_upstream_connect_attempt_total 22356
telemt_upstream_connect_success_total 22255
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 22255
telemt_upstream_connect_attempts_per_request{bucket="2"} 45
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12614
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9609
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 4646
telemt_me_reconnect_success_total 4621
telemt_me_reader_eof_total 4730
telemt_me_idle_close_by_peer_total 4730
telemt_me_route_drop_no_conn_total 113698
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 135
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 721
telemt_desync_full_logged_total 270
telemt_desync_suppressed_total 451
telemt_desync_frames_bucket_total{bucket="1_2"} 209
telemt_desync_frames_bucket_total{bucket="3_10"} 252
telemt_desync_frames_bucket_total{bucket="gt_10"} 260
telemt_pool_swap_total 8
telemt_pool_force_close_total 300
telemt_me_writer_removed_unexpected_total 4730
telemt_me_writer_restored_same_endpoint_total 4601
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 282708
telemt_user_connections_current{user="hello"} 829
telemt_user_octets_from_client{user="hello"} 2996128608 (2.79 GB)
telemt_user_octets_to_client{user="hello"} 88211939708 (82.15 GB)
telemt_user_unique_ips_current{user="hello"} 102
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 34179.1 (9h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149983
telemt_connections_bad_total 1038
telemt_handshake_timeouts_total 22297
telemt_upstream_connect_attempt_total 72300
telemt_upstream_connect_success_total 71310
telemt_upstream_connect_fail_total 457
telemt_upstream_connect_attempts_per_request{bucket="1"} 71304
telemt_upstream_connect_attempts_per_request{bucket="2"} 463
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23158
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 457
telemt_me_keepalive_timeout_total 1151
telemt_me_reconnect_attempts_total 42805
telemt_me_reconnect_success_total 42732
telemt_me_reader_eof_total 43799
telemt_me_idle_close_by_peer_total 43798
telemt_me_route_drop_no_conn_total 49635
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
telemt_me_writer_removed_unexpected_total 43879
telemt_me_writer_restored_same_endpoint_total 42707
telemt_me_writer_removed_unexpected_minus_restored_total 1172
telemt_user_connections_total{user="hello"} 100318
telemt_user_connections_current{user="hello"} 346
telemt_user_octets_from_client{user="hello"} 975323468 (930.14 MB)
telemt_user_octets_to_client{user="hello"} 40208022100 (37.45 GB)
telemt_user_unique_ips_current{user="hello"} 38
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 34177.9 (9h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 295294
telemt_connections_bad_total 97230
telemt_handshake_timeouts_total 7898
telemt_upstream_connect_attempt_total 48083
telemt_upstream_connect_success_total 47793
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 47792
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27571
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20087
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 635
telemt_me_reconnect_attempts_total 20523
telemt_me_reconnect_success_total 20469
telemt_me_reader_eof_total 21602
telemt_me_idle_close_by_peer_total 21599
telemt_me_route_drop_no_conn_total 74806
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 144
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 453
telemt_desync_full_logged_total 169
telemt_desync_suppressed_total 284
telemt_desync_frames_bucket_total{bucket="1_2"} 121
telemt_desync_frames_bucket_total{bucket="3_10"} 165
telemt_desync_frames_bucket_total{bucket="gt_10"} 167
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 21610
telemt_me_writer_restored_same_endpoint_total 20448
telemt_me_writer_removed_unexpected_minus_restored_total 1162
telemt_user_connections_total{user="hello"} 181620
telemt_user_connections_current{user="hello"} 467
telemt_user_octets_from_client{user="hello"} 1470378752 (1.37 GB)
telemt_user_octets_to_client{user="hello"} 53457072068 (49.79 GB)
telemt_user_unique_ips_current{user="hello"} 66
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 34176.8 (9h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 157762
telemt_connections_bad_total 12859
telemt_handshake_timeouts_total 4707
telemt_upstream_connect_attempt_total 26720
telemt_upstream_connect_success_total 26617
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 26617
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16472
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10144
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 294
telemt_me_reconnect_attempts_total 5973
telemt_me_reconnect_success_total 5962
telemt_me_reader_eof_total 6075
telemt_me_idle_close_by_peer_total 6075
telemt_me_route_drop_no_conn_total 46684
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 143
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 155
telemt_desync_full_logged_total 68
telemt_desync_suppressed_total 87
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 78
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 9
telemt_pool_force_close_total 213
telemt_me_writer_removed_unexpected_total 6075
telemt_me_writer_restored_same_endpoint_total 5941
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 131117
telemt_user_connections_current{user="hello"} 286
telemt_user_octets_from_client{user="hello"} 1308543104 (1.22 GB)
telemt_user_octets_to_client{user="hello"} 49097408776 (45.73 GB)
telemt_user_unique_ips_current{user="hello"} 32
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 34175.5 (9h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 303937
telemt_connections_bad_total 6395
telemt_handshake_timeouts_total 127908
telemt_upstream_connect_attempt_total 47634
telemt_upstream_connect_success_total 47303
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 47303
telemt_upstream_connect_attempts_per_request{bucket="2"} 155
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19002
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_keepalive_timeout_total 646
telemt_me_reconnect_attempts_total 21990
telemt_me_reconnect_success_total 21976
telemt_me_reader_eof_total 23177
telemt_me_idle_close_by_peer_total 23176
telemt_me_route_drop_no_conn_total 75895
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 144
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 214
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 144
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 4
telemt_pool_force_close_total 114
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 23190
telemt_me_writer_restored_same_endpoint_total 21951
telemt_me_writer_removed_unexpected_minus_restored_total 1239
telemt_user_connections_total{user="hello"} 164217
telemt_user_connections_current{user="hello"} 373
telemt_user_octets_from_client{user="hello"} 2255967120 (2.10 GB)
telemt_user_octets_to_client{user="hello"} 37198650088 (34.64 GB)
telemt_user_unique_ips_current{user="hello"} 43
```